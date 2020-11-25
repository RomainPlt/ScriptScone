# ScriptScone

only run "run_demo" and it should work if everything's perfect

Run you app in a local CAS.
	
		./run_demo [-tag] 
		./run_demo -p ~/path/to/app/ -n my_app -b gradle	
		
		-p --path_to_app    Absolute path. You need to have a docker-compose in the folder you point. Default: ~/Documents/rest\ app/demo
		-n --name           Your app's name need to be the one you use to run docker-compose? Default: demo
		-b --builder        docker or gradle ? Default: gradle
		-d --dockerfile     Default: Dockerfile-trusted (only for docker)
		-i --image_name     Image name for building in docker. Default: romainplt/demo (only for docker)
		"
