# prev.plsql.ru

Как скопировать и запустить oracle-dba.ru на свой хост с использованием docker контейнера:

Инсталлируете docker, далее:

    docker pull marley/centos6-for-dev
    docker run -i -t –rm -p 80:8080 –-name oradev marley/centos6-for-dev /bin/bash

<br/>

    source ~/.bash_profile
    cd /projects
    git clone --depth=1 https://github.com/oradev/oradev.github.io
    cd oradev.github.io
    gem install jekyll
    jekyll serve --watch  --host 0.0.0.0 --port 8080


<br/>

Остается в браузере подключиться к localhost