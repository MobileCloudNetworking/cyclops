# cyclops
A generic rating-charging-billing framework for cloud services. Cyclops is a micro-services framework with each micro-service performing a key functional task to enable seamless support for any billing or pricing strategy. It enables unified, consolidated billing combining not only cloud data sources but multiple application metric streams as required.

Interested in using Cyclops? Get the source code and related details from the project's landing page: <a href="http://icclab.github.io/cyclops/">http://icclab.github.io/cyclops/</a>.

# Quick Installation Guide
For your convenience, a set of bash scripts are provided that will allw you to setup cyclops service in a vm (or a set of vms) quickly. Simple execute the scripts in this order -
<pre><code>cd scripts
chmod +x *
./pre-req.sh
./cyclopsudr.sh
./cycloprc.sh
./cyclopsbilling.sh
./cyclopsdashboard.sh</code></pre>
After you execute these scripts, your cyclops dashboard should be available at:
<pre>http://your-vm-public-ip:8080/dashboard/app/</pre>

## License

cyclops is licensed under the
[Apache License version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
See the file LICENSE.

# Made by

<div align="center" >
<a href='http://blog.zhaw.ch/icclab'>
<img src="https://raw.githubusercontent.com/icclab/hurtle/master/docs/figs/icclab_logo.png" title="cyclops" width=400px>
</a>
</div>

# Supported by

<div align="center" >
<a href='http://blog.zhaw.ch/icclab'>
<img src="https://raw.githubusercontent.com/icclab/hurtle/master/docs/figs/mcn_logo.png" title="mobile cloud networking" width=400px>
</a>
</div>
