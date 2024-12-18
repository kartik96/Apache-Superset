### Install Apache Superset on MacOS


Clone the superet repository from github using the following command on the terminal:

``` 
git clone --depth=1  https://github.com/apache/superset.git

Ensure that the Docker application is installed on your laptop and that you have completed the sign-up process

After that run the follwong command to install the docker image of superset

```
export TAG=3.1.1
docker compose -f docker-compose-image-tag.yml up

That's it! Now let's run and test if it works. Open your browser and paste the following URL:

```
http://localhost:8088/

You should see the following screen once the page loads successfully:


Log in to Apache Superset using the following credentials:

Username: admin
Password: admin

And voilà! You're now logged in to Apache Superset and can start exploring the dashboards. 🎉
