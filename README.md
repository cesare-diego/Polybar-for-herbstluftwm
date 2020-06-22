# Polybar-for-herbstluftwm

# Polybar feito para uso em Arch Linux com a WM herbstluftwm.

# Instalaçao do polybar

		git clone https://aur.archlinux.org/polybar.git
		cd polybar
		makepkg -si

# Configuraçoes

		cp -r /usr/share/doc/polybar ~/.config

Todas as configuraçoes sao feitas dentro de .config/polybar/config

# Como usar essas configuraçoes?

![alt text](https://github.com/cesare-diego/Polybar-for-herbstluftwm/blob/master/Examples/example_polybar.png)

Para usar essas configuraçoes voce deve.

		Primeiro

		Clonar este repositorio
		Entrar em .config/polybar e mover o config original com o seguinte comando

		mv config config_backup


		Copiar as configuraçoes para seus respectivos diretorios

		cp ~/Polybar-for-herbstluftwm/polybar/config ~/.config/polybar
		cd ~/Polybar-for-herbstluftwm/fonts
		cp -r * /usr/share/fonts

		Setar o polybar para iniciar com  sistema

		Se voce estiver usando o herbstluftwm enato basta apenas editar o arquivo restart,
		e adicionar a linha 

		polybar -r mybar &

Pronto, basta reiniciar seu sistema, e se tudo deu certo o polybar estara funcionando corretamente.

