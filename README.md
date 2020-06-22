
<h1>Task Overview:</h1>
<ol>
<li>Create Container image that has Jenkins installed using dockerfile.</li>
<li>When we launch this image, it should automatically starts Jenkins service in the container.</li>
<li>Create a job chain of Job1, Job2, Job3 using build pipeline plugin in Jenkins.</li.
<li>JOB1: Pull the Github repo automatically when some developers push repo to Github.</li>
<li> JOB2: Test your app wheateher working or not.</li>
<li> JOB3: If the app is not working than automatically start the containner again.</li>
</ol>

<h2>Software Required:</h2>
<ol>
<li>Github</li>
<li>Jenkins</li>
<li>Docker</li>
</ol>

<h2>Project Description</h2>
<h3>Creating Dockerfile for Jenkins</h3>
 
![dockerfile](https://raw.githubusercontent.com/yashbajpai98/task2LW/master/task2-images/dockerfile.PNG)

Now, Build Image: docker build -t jenkins:v1
 ![3](https://raw.githubusercontent.com/yashbajpai98/task2LW/master/task2-images/3.PNG)
 
Now, Launch a new container through this image of jenkins:v1 so that jenkins get automatically launched.
 
