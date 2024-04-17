1) Shells in linux
  - Bourne Shell(sh)
  - C Shell(csh) = used for c programming language
  - KirbShell(ksh)
  - Bourne Again Shell(Bash)
  - Debian Almquist Shell(dash) - faster
  - Z Shell(zsh) - most powerfull shell

 2) History commands
    - HISTCONTROL="ignorespace"
    - HISTCONTROL="ignoredups"
    - HISTCONTROL="erasedups"
    - HISTIGNORE="history*"
    - HISTTIMEFORMAT="%h %d %H: %M: %S -> "

 3) File Globs:
    - Asterisk(*) e.g. file*.txt
    - Question Mark(?) e.g. file??.txt
    - Character Set([]) e.g. file[123].txt , file[1-5].txt

4) echo usefull commands
   - echo "MY    Name is Rahul "
   - echo {1..10}
   - echo {a..z}
   - echo {1..100..2}
   - echo {a..z..2}
   - echo "MY name is $(whoami)"
   - echo "MY name is `whoami`"

5) Processes command
  -> ps -eh
  -> ps -elf
  -> ps -t
  -> ps -a
  -> ps -f
  -> htop

6)  process priority
    - most nice = 19
    - default priority = 0
    - least nice = -19
    - watch ps
    - ps -elf
    
crontab-generator.org
systemctl list-unit-files -t service
 crontab commands
 - crontab -e
 - crontab -l
 - crontab location = "/var/spool/cron/crontabs"
 - crontab for hoourtly seddule of work - /etc/cron.hourly
 - man cron
 - daemon to execute scheduled commands

The allow Files - "/etc/at.allow" , "/etc/cron.allow"
The deny Files - "/etc/at.deny" , "/etc/cron.deny"
 less /etc/security/access.conf => this file has more info
