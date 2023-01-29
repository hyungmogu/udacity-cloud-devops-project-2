fix_permission_denied:
	chmod +x update.sh
	chmod +x create.sh

deploy:
	sh create.sh udagram-network final-project-starter.yml server-parameters.json &&\
	sh create.sh udagram-server final-project-starter-server.yml server-parameters.json

delete:
	sh delete.sh udagram-network
	sh delete.sh udagram-server