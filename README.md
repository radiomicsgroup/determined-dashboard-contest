# determined dashboard contest


<img src="https://media2.giphy.com/media/u5chXT0G9B771HcW1L/giphy.gif"/>

The idea is to use the example csv to create one or more dashboards that you believe are important to see the cluster's use. I'm out of ideas. Please create a folder in this repo  under the folder src with your cluster username and inside create one or more python files with your code and a requirements.txt file with the libraries used.

With the code that you create, I will create a web service to generate the web dashboard.

## Data Description

- genid: auto generated string Id
- id: docker container id 
- name: auto generated docker container name 
- cpu: cpu % usage in the machine 
- mem: memory ussage in bytes
- memperc: memory usage percent in the machine
- netin: network traffic in
- netout: network traffic out
- blockin: data hd read data
- blockout: data hd write data
- image: docker image used in the container 
- detuser: cluster user 
- ip: Ip address of the host of the running container
- date: timestamp of the data.
