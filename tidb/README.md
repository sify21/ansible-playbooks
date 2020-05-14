ansible playbooks for installing tidb cluster on centos7 using binaries. including:
- fetch  
  download required binaries
- create_user  
  create tidb user on servers. You should provide ROOT_PWD and TIDB_PWD environment variables. see also [How do I prevent commands from showing up in Bash history?](https://stackoverflow.com/questions/6475524/how-do-i-prevent-commands-from-showing-up-in-bash-history/29188490#29188490)
