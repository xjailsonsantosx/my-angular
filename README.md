# my-angular

### Before installing the latest version of Node.js, you must add its PPA to Ubuntu… This repository is provided by the official package mainterner

	sudo apt install curl
		curl -V
			curl 7.58.0

### Latest Node
	sudo curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -

### Install node
	sudo apt install nodejs
		node -v 
			v10.11.0
		<!-- npm install --save-dev @angular-devkit/build-angular -->
		npm -v
			6.4.1
### Angular
	sudo npm install -g @angular/cli
	sudo npm update -g	
	
	sudo chown -R $USER:$(id -gn $USER) /home/jailson/.config 
	sudo ng new my-app		
	cd my-app
	ng serve -o (ou --open para abrir o navegador assim que o servidor estiver pronto)
