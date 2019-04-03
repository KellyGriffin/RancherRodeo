 # Add the K3S cluster in to Rancher

Now we need to import our K3S Kubernetes environment into Rancher.  For this we will go back to our Rancher server's web page and login using the credentials you created before.

In the Rancher UI:
```
Click "Add Cluster".

Click "Import existing cluster" and give it a name (this can be any name you like) and click create

Copy the kubectl command at the bottom of the page and paste it into the Master Server via the Katacoda webpage on the Master Server,

Once that has been copied and pasted - you can go back to your Rancher Server and click "Done".
```

That is it - you have now deployed a Rancher Server, installed K3S and imported it into Rancher.  Let's have a look around.

_Before exiting - feel free to have a look around and see what else you can do.  If you are ready though - feel free to hit continue and move onto another demonstration of Rancher and Kubernetes._