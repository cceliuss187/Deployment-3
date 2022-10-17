<h1>CI/CD pipeline deployment 3 </h1>

<h2>(1) Set up and configure your Jenkins environment within default VPC.</h2>


- install and configure jenkins on an EC2 to listen on port 22 to be able to SSH into the EC2, port 5000 and 8080 to access Jenkins' web interface.

- On the EC2 install default-jre which is a Java Runtime Environment (JRE) which is required to run Java programs, python3-pip which tool for installing Python packages ,
  python3.10-venv which is a virtual environment for python so that the Python interpreter, libraries, and scripts installed on here are totally isolated from those installed 
  on the virtual machine. and nginx which is a high-performance HTTP web server that includes reverse proxy, load balancing, mail proxy, and HTTP cache capabilities. 
  
  
<h2>(2) Configure and connect a jenkins agent to jenkins.</h2>

- This jenkins agent is basically a machine which executes tasks when ordered to do so by the jenkins master.


<h2>(3) Create a multibranch pipeline build in jenkins.</h2>

- This is where the steps on how to build, test, clean, and deploy the application will be orchestrated.
