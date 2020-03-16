---


---

<h1 id="how-to-configure-jupyter-notebook-on-azure">How to configure Jupyter Notebook on Azure</h1>
<h2 id="create-an-account">Create an account</h2>
<p>You can create an account on:<br>
<a href="https://notebooks.azure.com/">https://notebooks.azure.com/</a></p>
<p>And you can upload your notebooks or create your first one. Open one Notebook and you should see something like that:</p>
<p><img src="https://files.slack.com/files-pri/T7HSLC12Q-FV389DB3L/screenshot_2020-03-16_08.53.28.png" alt=""></p>
<p>With Python 3 written in the top right corner.<br>
First we need to open it with Python 3.6. So click on:</p>
<pre><code>Kernel, and choose Change Kernel, and Python3.6
</code></pre>
<p>Now you can see Python 3.6 on the top right:<br>
<img src="https://files.slack.com/files-pri/T7HSLC12Q-FV38X33NE/screenshot_2020-03-16_09.07.14.png" alt=""></p>
<h2 id="install-requiere-packages">Install requiere packages:</h2>
<p>Click on</p>
<pre><code>File / Open
</code></pre>
<p>And you can see the following screen:</p>
<p><img src="https://files.slack.com/files-pri/T7HSLC12Q-FV4JARWTV/screenshot_2020-03-16_at_09.07.43.png" alt=""></p>
<p>Click at the top right on</p>
<pre><code>New / Terminal
</code></pre>
<p>And you can see in a new tab this:</p>
<p><img src="https://files.slack.com/files-pri/T7HSLC12Q-F0101JSJRQU/screenshot_2020-03-16_at_09.09.30.png" alt=""></p>
<p>You can execute the following lines in the terminal:</p>
<pre><code>mkdir gateTools
git clone https://github.com/OpenGATE/GateTools.git gateTools/
cd gateTools/
/home/nbuser/anaconda3_501/bin/pip install --user -e .
</code></pre>
<p>The last line can take some minutes to install all require packages.</p>
<h2 id="last-few-things">Last few things:</h2>
<p>Now you can come back to you preferred Jupyter Notebook and execute it. But you need to know 2 things:</p>
<ol>
<li>If you open a new Jupyter Notebook, you should need to change the Python version from 3 to 3.6 (like in the first chapter)</li>
<li>If you disconnect from Microsoft Azure, you should redo the installation of require packages (like in the second chapter)</li>
<li>If a package is missing, you can install it like in the second chapter:</li>
</ol>
<pre><code>Open a terminal
pip install --user &lt;packageName&gt;
</code></pre>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

