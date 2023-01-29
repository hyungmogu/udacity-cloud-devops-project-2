fix_permission_denied:
	chmod +x update.sh
	chmod +x create.sh

deploy:
	sh create.sh udagram-network final-project-starter-network.yml network-parameters.json &&\
	sh create.sh udagram-server final-project-starter-server.yml server-parameters.json udagram-network

delete:
	sh delete.sh udagram-network &&\
	sh delete.sh udagram-server