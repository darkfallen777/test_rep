 GITSTATUS_LOG_LEVEL=DEBUG
[powerlevel10k] fetching gitstatusd .. -
[ERROR]: gitstatus failed to initialize.


  Zsh log (/tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.xtrace.log):

    +(anon):7> setopt monitor
    +(anon):9> ((  ! _GITSTATUS_STATE_POWERLEVEL9K  ))
    +(anon):10> [[ -r /proc/version && 'Linux version 4.4.0-19041-Microsoft (Microsoft@Microsoft.com) (gcc version 5.4.0 (GCC) ) #1237-Microsoft Sat Sep 11 14:32:00 PST 2021' == *Microsoft* ]]
    +(anon):11> lock_fd=-1
    +(anon):18> typeset -gi '_GITSTATUS_LOCK_FD_POWERLEVEL9K=lock_fd'
    +(anon):20> [[ linux-gnu == cygwin* ]]
    +(anon):41> sysopen -r -o cloexec -u resp_fd /proc/self/fd/17
    +(anon):41> _gitstatus_daemon_p9k_
    +(anon):44> typeset -gi 'GITSTATUS_DAEMON_PID_POWERLEVEL9K=106'
    +_gitstatus_daemon_p9k_:1> local -i pipe_fd
    +(anon):46> [[ 20 == <1-> ]]
    +(anon):47> typeset -gi '_GITSTATUS_RESP_FD_POWERLEVEL9K=resp_fd'
    +(anon):48> typeset -gi '_GITSTATUS_STATE_POWERLEVEL9K=1'
    +(anon):51> ((  ! async  ))
    +(anon):52> ((  _GITSTATUS_CLIENT_PID_POWERLEVEL9K == sysparams[pid]  ))
    +(anon):54> local pgid
    +(anon):55> ((  0 < 20  ))
    +(anon):56> [[ -t 20 ]]
    +(anon):57> sysread -s 20 -t 5.0000000000 -i 20 'pgid[$#pgid+1]'
    +(anon):55> ((  20 < 20  ))
    +(anon):59> [[ '                 106' == \ #<1-> ]]
    +(anon):60> typeset -gi 'GITSTATUS_DAEMON_PID_POWERLEVEL9K=pgid'
    +(anon):62> sysopen -w -o cloexec -u req_fd -- /tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.fifo
    +(anon):63> [[ 18 == <1-> ]]
    +(anon):64> typeset -gi '_GITSTATUS_REQ_FD_POWERLEVEL9K=req_fd'
    +(anon):66> print -nru 18 -- $'}hello\C-_\C-^'
    +(anon):67> local expected=$'}hello\C-_0\C-^' actual
    +(anon):68> ((  1  ))
    +(anon):68> [[ ! -t 1 ]]
    +(anon):71> local -F deadline=1
    +(anon):73> true
    +(anon):74> [[ -t 20 ]]
    +(anon):75> sysread -s 1 -t 5.0000000000 -i 20 actual
    +(anon):76> [[ $'}hello\C-_0\C-^' == * ]]
    +(anon):77> [[ $'\C-A' !=  ]]
    +(anon):85> ((  EPOCHREALTIME < deadline  ))
    +(anon):86> ((  deadline > 0  ))
    +(anon):87> deadline=0
    +(anon):88> ((  stderr_fd  ))
    +(anon):89> unsetopt xtrace

  Daemon log (/tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.daemon.log):

    +_gitstatus_daemon_p9k_:3> local pgid=106
    +_gitstatus_daemon_p9k_:4> [[ 106 == <1-> ]]
    +_gitstatus_daemon_p9k_:5> cd -q /
    +_gitstatus_daemon_p9k_:90> ((  lock_fd == -1  ))
    +_gitstatus_daemon_p9k_:90> return
    +_gitstatus_daemon_p9k_:9> trap '' PIPE
    +_gitstatus_daemon_p9k_:11> local uname_sm
    +_gitstatus_daemon_p9k_:12> uname_sm=+_gitstatus_daemon_p9k_:12> uname -sm
    +_gitstatus_daemon_p9k_:12> uname_sm='linux x86_64'
    +_gitstatus_daemon_p9k_:13> [[ 'linux x86_64' == [^\ ]##\ [^\ ]## ]]
    +_gitstatus_daemon_p9k_:14> local uname_s=linux
    +_gitstatus_daemon_p9k_:15> local uname_m=x86_64
    +_gitstatus_daemon_p9k_:17> [[ '' == <1-> ]]
    +_gitstatus_daemon_p9k_:20> local cpus
    +_gitstatus_daemon_p9k_:21> ((  ! 1  ))
    +_gitstatus_daemon_p9k_:21> [[ linux == linux ]]
    +_gitstatus_daemon_p9k_:23> ((  ! 1  ))
    +_gitstatus_daemon_p9k_:23> cpus=+_gitstatus_daemon_p9k_:23> getconf _NPROCESSORS_ONLN
    +_gitstatus_daemon_p9k_:23> cpus=4
    +_gitstatus_daemon_p9k_:27> args+=( -t 8 )
    +_gitstatus_daemon_p9k_:30> mkfifo -- /tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.fifo
    +_gitstatus_daemon_p9k_:31> print -rnu 13 -- '                 106'
    +_gitstatus_daemon_p9k_:33> zf_rm -- /tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.fifo
    +_gitstatus_daemon_p9k_:35> local _gitstatus_zsh_daemon _gitstatus_zsh_version _gitstatus_zsh_downloaded
    +_gitstatus_daemon_p9k_:43> local gitstatus_plugin_dir_var=_gitstatus_plugin_dir_p9k_
    +_gitstatus_daemon_p9k_:44> local gitstatus_plugin_dir=/root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_daemon_p9k_:45> set -- -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_daemon_p9k_:47> [[ 1 == (|-|+)<1-> ]]
    +_gitstatus_daemon_p9k_:48> source /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install
    +/root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install:472> [ -z '' ']'
    +/root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install:473> _gitstatus_install_main /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:1> [ -n 5.8.1 ']'
    +_gitstatus_install_main:2> emulate -L sh -o no_unset
    +_gitstatus_install_main:7> local argv1=/root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:8> shift
    +_gitstatus_install_main:10> local no_check='' no_install='' uname_s='' uname_m='' gitstatus_dir='' dl_status='' e=''
    +_gitstatus_install_main:11> local opt='' OPTARG='' OPTIND=1
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case d (h)
    +_gitstatus_install_main:14> case d (n)
    +_gitstatus_install_main:14> case d (f)
    +_gitstatus_install_main:14> case d (d)
    +_gitstatus_install_main:55> [ -n '' ']'
    +_gitstatus_install_main:59> [ -z /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus ']'
    +_gitstatus_install_main:63> gitstatus_dir=/root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case s (h)
    +_gitstatus_install_main:14> case s (n)
    +_gitstatus_install_main:14> case s (f)
    +_gitstatus_install_main:14> case s (d)
    +_gitstatus_install_main:14> case s (p)
    +_gitstatus_install_main:14> case s (e)
    +_gitstatus_install_main:14> case s (m)
    +_gitstatus_install_main:14> case s (s)
    +_gitstatus_install_main:99> [ -n '' ']'
    +_gitstatus_install_main:103> [ -z linux ']'
    +_gitstatus_install_main:107> uname_s=linux
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case m (h)
    +_gitstatus_install_main:14> case m (n)
    +_gitstatus_install_main:14> case m (f)
    +_gitstatus_install_main:14> case m (d)
    +_gitstatus_install_main:14> case m (p)
    +_gitstatus_install_main:14> case m (e)
    +_gitstatus_install_main:14> case m (m)
    +_gitstatus_install_main:88> [ -n '' ']'
    +_gitstatus_install_main:92> [ -z x86_64 ']'
    +_gitstatus_install_main:96> uname_m=x86_64
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case p (h)
    +_gitstatus_install_main:14> case p (n)
    +_gitstatus_install_main:14> case p (f)
    +_gitstatus_install_main:14> case p (d)
    +_gitstatus_install_main:14> case p (p)
    +_gitstatus_install_main:66> [ -n '' ']'
    +_gitstatus_install_main:70> [ -z 'printf '\''\001'\'' >&13' ']'
    +_gitstatus_install_main:74> dl_status='printf '\''\001'\'' >&13'
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case e (h)
    +_gitstatus_install_main:14> case e (n)
    +_gitstatus_install_main:14> case e (f)
    +_gitstatus_install_main:14> case e (d)
    +_gitstatus_install_main:14> case e (p)
    +_gitstatus_install_main:14> case e (e)
    +_gitstatus_install_main:77> [ -n '' ']'
    +_gitstatus_install_main:81> [ -z 13 ']'
    +_gitstatus_install_main:85> e=13
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m x86_64 -p 'printf '\''\001'\'' >&13' -e 13 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:115> shift 11
    +_gitstatus_install_main:117> : 13
    +_gitstatus_install_main:118> : /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:120> [ -n '' -a -n '' ']'
    +_gitstatus_install_main:125> [ -z linux ']'
    +_gitstatus_install_main:129> [ -z x86_64 ']'
    +_gitstatus_install_main:134> local daemon=''
    +_gitstatus_install_main:135> local cache_dir=/root/.cache/gitstatus
    +_gitstatus_install_main:137> [ -z '' ']'
    +_gitstatus_install_main:138> [ -n '' ']'
    +_gitstatus_install_main:142> [ -z '' -a -e /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/usrbin/gitstatusd ']'
    +_gitstatus_install_main:145> [ -n '' ']'
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";'
    +_gitstatus_install_main:166> uname_s_glob=cygwin_nt-10.0
    +_gitstatus_install_main:166> uname_m_glob=i686
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3
    +_gitstatus_install_main:168> [ -z cygwin_nt-10.0 -o -z i686 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3 ']'
    +_gitstatus_install_main:177> case linux (cygwin_nt-10.0)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";'
    +_gitstatus_install_main:166> uname_s_glob=cygwin_nt-10.0
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.1
    +_gitstatus_install_main:166> sha256=c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f
    +_gitstatus_install_main:168> [ -z cygwin_nt-10.0 -o -z x86_64 -o -z gitstatusd-linux-x86_64 -o -z v1.5.1 -o -z c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f ']'
    +_gitstatus_install_main:177> case linux (cygwin_nt-10.0)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";'
    +_gitstatus_install_main:166> uname_s_glob=darwin
    +_gitstatus_install_main:166> uname_m_glob=arm64
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a
    +_gitstatus_install_main:168> [ -z darwin -o -z arm64 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a ']'
    +_gitstatus_install_main:177> case linux (darwin)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";'
    +_gitstatus_install_main:166> uname_s_glob=darwin
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6
    +_gitstatus_install_main:168> [ -z darwin -o -z x86_64 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6 ']'
    +_gitstatus_install_main:177> case linux (darwin)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";'
    +_gitstatus_install_main:166> uname_s_glob=freebsd
    +_gitstatus_install_main:166> uname_m_glob=amd64
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442
    +_gitstatus_install_main:168> [ -z freebsd -o -z amd64 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442 ']'
    +_gitstatus_install_main:177> case linux (freebsd)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=aarch64
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225
    +_gitstatus_install_main:168> [ -z linux -o -z aarch64 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (aarch64)
    +_gitstatus_install_main:181> case x86_64 (*)
    +_gitstatus_install_main:183> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="armv6l";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="4bf5a0d0a082f544a48536ad3675930d5d2cc6a8cf906710045e0788f51192b3";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="armv6l";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="4bf5a0d0a082f544a48536ad3675930d5d2cc6a8cf906710045e0788f51192b3";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="armv6l";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="4bf5a0d0a082f544a48536ad3675930d5d2cc6a8cf906710045e0788f51192b3";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=armv6l
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.1
    +_gitstatus_install_main:166> sha256=4bf5a0d0a082f544a48536ad3675930d5d2cc6a8cf906710045e0788f51192b3
    +_gitstatus_install_main:168> [ -z linux -o -z armv6l -o -z gitstatusd-linux-x86_64 -o -z v1.5.1 -o -z 4bf5a0d0a082f544a48536ad3675930d5d2cc6a8cf906710045e0788f51192b3 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (armv6l)
    +_gitstatus_install_main:181> case x86_64 (*)
    +_gitstatus_install_main:183> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="armv7l";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="2b9deb29f86c8209114b71b94fc2e1ed936a1658808a1bee46f4a82fd6a1f8cc";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="armv7l";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="2b9deb29f86c8209114b71b94fc2e1ed936a1658808a1bee46f4a82fd6a1f8cc";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="armv7l";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="2b9deb29f86c8209114b71b94fc2e1ed936a1658808a1bee46f4a82fd6a1f8cc";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=armv7l
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.1
    +_gitstatus_install_main:166> sha256=2b9deb29f86c8209114b71b94fc2e1ed936a1658808a1bee46f4a82fd6a1f8cc
    +_gitstatus_install_main:168> [ -z linux -o -z armv7l -o -z gitstatusd-linux-x86_64 -o -z v1.5.1 -o -z 2b9deb29f86c8209114b71b94fc2e1ed936a1658808a1bee46f4a82fd6a1f8cc ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (armv7l)
    +_gitstatus_install_main:181> case x86_64 (*)
    +_gitstatus_install_main:183> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="armv8l";  file="gitstatusd-${uname_s}-aarch64";        version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="armv8l";  file="gitstatusd-${uname_s}-aarch64";        version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="armv8l";  file="gitstatusd-${uname_s}-aarch64";        version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=armv8l
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225
    +_gitstatus_install_main:168> [ -z linux -o -z armv8l -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (armv8l)
    +_gitstatus_install_main:181> case x86_64 (*)
    +_gitstatus_install_main:183> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="56d55e2e9a202d3072fa612d8fa1faa61243ffc86418a7fa64c2c9d9a82e0f64";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="56d55e2e9a202d3072fa612d8fa1faa61243ffc86418a7fa64c2c9d9a82e0f64";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="56d55e2e9a202d3072fa612d8fa1faa61243ffc86418a7fa64c2c9d9a82e0f64";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=i686
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=56d55e2e9a202d3072fa612d8fa1faa61243ffc86418a7fa64c2c9d9a82e0f64
    +_gitstatus_install_main:168> [ -z linux -o -z i686 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 56d55e2e9a202d3072fa612d8fa1faa61243ffc86418a7fa64c2c9d9a82e0f64 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (i686)
    +_gitstatus_install_main:181> case x86_64 (*)
    +_gitstatus_install_main:183> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="ppc64le"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="1afd072c8c26ef6ec2d9ac11cef96c84cd6f10e859665a6ffcfb6112c758547e";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="ppc64le"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="1afd072c8c26ef6ec2d9ac11cef96c84cd6f10e859665a6ffcfb6112c758547e";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="ppc64le"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="1afd072c8c26ef6ec2d9ac11cef96c84cd6f10e859665a6ffcfb6112c758547e";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=ppc64le
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=1afd072c8c26ef6ec2d9ac11cef96c84cd6f10e859665a6ffcfb6112c758547e
    +_gitstatus_install_main:168> [ -z linux -o -z ppc64le -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 1afd072c8c26ef6ec2d9ac11cef96c84cd6f10e859665a6ffcfb6112c758547e ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (ppc64le)
    +_gitstatus_install_main:181> case x86_64 (*)
    +_gitstatus_install_main:183> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-x86_64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304
    +_gitstatus_install_main:168> [ -z linux -o -z x86_64 -o -z gitstatusd-linux-x86_64 -o -z v1.5.4 -o -z 9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case x86_64 (x86_64)
    +_gitstatus_install_main:188> [ -z '' ']'
    +_gitstatus_install_main:190> local daemon=/root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/usrbin/gitstatusd-linux-x86_64
    +_gitstatus_install_main:191> [ ! -e /root/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/usrbin/gitstatusd-linux-x86_64 ']'
    +_gitstatus_install_main:192> daemon=/root/.cache/gitstatus/gitstatusd-linux-x86_64
    +_gitstatus_install_main:193> [ -e /root/.cache/gitstatus/gitstatusd-linux-x86_64 ']'
    +_gitstatus_install_main:193> daemon=''
    +_gitstatus_install_main:195> [ -n '' ']'
    +_gitstatus_install_main:203> [ -n '' ']'
    +_gitstatus_install_main:208> local daemon=/root/.cache/gitstatus/gitstatusd-linux-x86_64
    +_gitstatus_install_main:210> [ -n '' ']'
    +_gitstatus_install_main:214> [ ! -d /root/.cache/gitstatus ']'
    +_gitstatus_install_main:214> [ ! -w /root/.cache/gitstatus ']'
    +_gitstatus_install_main:237> [ -n '' -a '(' '(' -d '' -a -w '' ')' -o ! '(' -d /tmp -a -w /tmp ')' ')' ']'
    +_gitstatus_install_main:240> local tmp=/tmp
    +_gitstatus_install_main:242> command -v mktemp
    +_gitstatus_install_main:243> tmpdir=+_gitstatus_install_main:243> mktemp -d /tmp/gitstatus-install.XXXXXXXXXX
    +_gitstatus_install_main:243> tmpdir=/tmp/gitstatus-install.jsOZa9RHVN
    +_gitstatus_install_main:268> command -v curl
    +_gitstatus_install_main:325> local url1=https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-x86_64.tar.gz
    +_gitstatus_install_main:326> local url2=https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-x86_64.tar.gz
    +_gitstatus_install_main:327> local sig='INT QUIT TERM ILL PIPE'
    +_gitstatus_install_main:363> local trapped=''
    +_gitstatus_install_main:364> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:366> local pid1=113
    +_gitstatus_install_main:365> fetch 1 https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-x86_64.tar.gz
    +fetch:1> [ 1 '!=' 1 ']'
    +fetch:7> local cmd part url ret
    +fetch:8> cmd=curl -kfsSL
    +fetch:9> part=0
    +fetch:10> true
    +fetch:11> [ 0 '=' 2 ']'
    +fetch:14> [ 0 '=' 0 ']'
    +fetch:15> url=https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-x86_64.tar.gz
    +fetch:19> run_cmd curl -kfsSL -- https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-x86_64.tar.gz
    +run_cmd:1> command -v curl
    +run_cmd:2> local trapped='' pid die ret
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:368> local pid2=114
    +run_cmd:7> ret=0
    +_gitstatus_install_main:370> local die='trap - INT QUIT TERM ILL PIPE; kill -- 113 114 2>/dev/null; wait -- 113 114 2>/dev/null; exit 1'
    +_gitstatus_install_main:367> fetch 2 https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-x86_64.tar.gz
    +run_cmd:8> [ 0 '=' 0 ']'
    +_gitstatus_install_main:371> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 113 114 2>/dev/null; wait -- 113 114 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:9> pid=115
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 115 2>/dev/null; wait -- 115 2>/dev/null; exit 1'
    +run_cmd:6> curl -kfsSL -- https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-x86_64.tar.gz
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 115 2>/dev/null; wait -- 115 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:372> [ -z '' ']'
    +fetch:1> [ 2 '!=' 1 ']'
    +_gitstatus_install_main:374> local n=''
    +run_cmd:12> [ -z '' ']'
    +_gitstatus_install_main:375> true
    +fetch:1> command -v sleep
    +run_cmd:13> wait -- 115
    +_gitstatus_install_main:376> [ -z 'printf '\''\001'\'' >&13' ']'
    +_gitstatus_install_main:376> eval 'printf '\''\001'\'' >&13'
    +fetch:2> run_cmd sleep 2
    +_gitstatus_install_main:376> printf '\001'
    +run_cmd:1> command -v sleep
    +_gitstatus_install_main:377> command -v sleep
    +run_cmd:2> local trapped='' pid die ret
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:378> sleep 1
    +run_cmd:7> ret=0
    +run_cmd:6> sleep 2
    +run_cmd:8> [ 0 '=' 0 ']'
    +run_cmd:9> pid=116
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 116 2>/dev/null; wait -- 116 2>/dev/null; exit 1'
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 116 2>/dev/null; wait -- 116 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:12> [ -z '' ']'
    +run_cmd:13> wait -- 116
    +run_cmd:14> ret=0
    +run_cmd:16> trap - INT QUIT TERM ILL PIPE
    +run_cmd:17> [ -z '' ']'
    +run_cmd:18> return 0
    +fetch:20> ret=0
    +fetch:21> [ 0 '=' 0 ']'
    +fetch:22> check_sha256 1
    +check_sha256:1> local data_file=/tmp/gitstatus-install.jsOZa9RHVN/1.tar.gz
    +check_sha256:2> local hash_file=/tmp/gitstatus-install.jsOZa9RHVN/1.tar.gz.sha256
    +check_sha256:3> local hash=''
    +check_sha256:5> command -v shasum
    +check_sha256:6> run_cmd shasum -b -a 256 -- /tmp/gitstatus-install.jsOZa9RHVN/1.tar.gz
    +run_cmd:1> command -v shasum
    +run_cmd:2> local trapped='' pid die ret
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +run_cmd:7> ret=0
    +run_cmd:8> [ 0 '=' 0 ']'
    +run_cmd:9> pid=120
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 120 2>/dev/null; wait -- 120 2>/dev/null; exit 1'
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 120 2>/dev/null; wait -- 120 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:6> shasum -b -a 256 -- /tmp/gitstatus-install.jsOZa9RHVN/1.tar.gz
    +run_cmd:12> [ -z '' ']'
    +run_cmd:13> wait -- 120
    +run_cmd:14> ret=0
    +run_cmd:16> trap - INT QUIT TERM ILL PIPE
    +run_cmd:17> [ -z '' ']'
    +run_cmd:18> return 0
    +check_sha256:7> IFS='' +check_sha256:7> read -r hash
    +check_sha256:8> hash=9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304
    +check_sha256:9> [ 64 -eq 64 ']'
    +check_sha256:27> [ 1 '=' 1 -a -z 9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304 -o 9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304 '=' 9633816e7832109e530c9e2532b11a1edae08136d63aa7e40246c0339b7db304 ']'
    +fetch:22> break
    +fetch:25> [ 0 '=' 0 ']'
    +fetch:25> break
    +fetch:30> echo -n
    +fetch:31> return 0
    +_gitstatus_install_main:382> [ -n 113 -a -e /tmp/gitstatus-install.jsOZa9RHVN/1.status ']'
    +_gitstatus_install_main:383> wait -- 113
    +_gitstatus_install_main:384> local ret=0
    +_gitstatus_install_main:385> pid1=''
    +_gitstatus_install_main:386> [ 0 '=' 0 ']'
    +_gitstatus_install_main:387> [ -n 114 ']'
    +_gitstatus_install_main:388> kill -- 114
    +_gitstatus_install_main:389> wait -- 114
    +run_cmd:13> trap - INT QUIT TERM ILL PIPE
    +run_cmd:13> kill -- 116
    +run_cmd:13> wait -- 116
    +run_cmd:13> exit 1
    +_gitstatus_install_main:391> n=1
    +_gitstatus_install_main:392> break
    +_gitstatus_install_main:419> trap - INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:421> [ -z 1 ']'
    +_gitstatus_install_main:431> tar -C /tmp/gitstatus-install.jsOZa9RHVN -xzf /tmp/gitstatus-install.jsOZa9RHVN/1.tar.gz
    /usr/bin/gzip: 1: ELF: not found
    /usr/bin/gzip: 3: : not found
    /usr/bin/gzip: 4: Syntax error: "(" unexpected
    tar: Child returned status 2
    tar: Error is not recoverable: exiting now
    +_gitstatus_install_main:431> exit
    +_gitstatus_install_main:447> local ret=2
    +_gitstatus_install_main:448> rm -rf -- /tmp/gitstatus-install.jsOZa9RHVN
    +_gitstatus_install_main:449> [ 2 '=' 0 ']'
    +_gitstatus_install_main:449> return
    +_gitstatus_daemon_p9k_:48> return
    +_gitstatus_daemon_p9k_:84> local -i ret=1
    +_gitstatus_daemon_p9k_:85> zf_rm -f -- /tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.lock /tmp/gitstatus.POWERLEVEL9K.0.46.1658390949.3.fifo
    +_gitstatus_daemon_p9k_:86> kill -- -106

  System information:

    zsh:      5.8.1
    uname -a: Linux eonteam-pc 4.4.0-19041-Microsoft #1237-Microsoft Sat Sep 11 14:32:00 PST 2021 x86_64 x86_64 x86_64 GNU/Linux

  If you need help, open an issue and attach this whole error message to it:

    https://github.com/romkatv/gitstatus/issues/new
