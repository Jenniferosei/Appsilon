
To build the Docker image: docker build -t app .

To run the Docker container: docker run -p 5000:5000 app


To run the playbook, use the command: ansible-playbook playbook.yml -i hosts.ini (replace hosts.ini with your own inventory file).
