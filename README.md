#Munin capistrano_deploy_uptime check plugin

![ capistrano_deploy_uptime ](https://raw.github.com/S1100/munin-plugin-capistrano_deploy_uptime/master/sample.png)
<pre><code>
</code></pre>
* * *
##INSTALLATION

###1. get the file
<pre><code>
# cd /usr/share/munin/plugins/
# wget https://raw.github.com/S1100/munin-plugin-capistrano_deploy_uptime/master/capistrano_deploy_uptime
# chmod 755 capistrano_deploy_uptime
# cd /etc/munin/plugins
# ln -s /usr/share/munin/plugins/capistrano_deploy_uptime .

</code></pre>

###2. Adapt for your deployment
<pre><code>
#  vi munin-run capistrano_deploy_uptime
Edit app1, app2
</code></pre>

###3. check the response
<pre><code>
#  time munin-run capistrano_deploy_uptime 
</code></pre>

###4. No problem, then
<pre><code>
# service munin-node restart
</code></pre>
