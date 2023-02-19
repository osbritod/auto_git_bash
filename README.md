# auto_git_bash
Sincronizar o servidor local (linux) com seu repositório no github

Com o código você pode sincronizar a cada x segundos o servidor local com o repositório escolhido



nohup while true; do git pull https://user:token@github.com/repo  --allow-unrelated-histories; date ; sleep 5; done

*nohup é para o código continuar executando mesmo quando fechar o terminal
