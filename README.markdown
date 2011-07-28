<h1>Consistency or Bust: Breaking a Riak Cluster</h1>
<p>This repository contains all the information for my presentation at OSCON Data 2011 on Wednesday July 27th, 2011 called Consistency or Bust: Breaking a Riak Cluster.</p>

<h2>Setting Up A Cluster</h2>
<p>Follow the instructions outlined within cluster_setup.pdf to install the pre-requisites needed to compile Riak from source. Once that is completed and you pull the Riak source from http://github.com/basho/riak, perform the following steps in order to build a five node cluster:
	<ol>
		<li>copy dev[1-5]_vars.config to ./riak/rel/vars</li>
		<li>copy makefile to ./riak</li>
		<li>type in terminal <code>make devrel</code></li>
	</ol>
</p>
