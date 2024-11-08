<h1> Qiskit Introductory Guide <h1\>

<h3>Guide Content</h3>

<p1> This guide briefly covers resources for setting up an environment to run Python code and to use the Qiskit software development kit (SDK). Then, there are several notebooks that provide an introduction of working with basic quantum circuits, measuring with primitives, transpiling, running simulations, queueing jobs on IBM quantum computers, visualizations, and dynamic circuits.</p1>

<H3>Installing and Setting up Your Environment</H3>

<p1>First, you need a working python install and a jupyter notebook environment to work in. There are several free and common options. This installation process varies from operating system to operating system. Here are some quick links to get setup:</p1>

<H5>Windows and MACOS</H5>
<ul>
<li>Step 1: <a href="https://www.geeksforgeeks.org/download-and-install-python-3-latest-version/#install-python-on-windows-10">Python</a>
<li>Step 2: <a href="https://jupyter.org/install">Jupyter Notebook</a>
<li>Optional Step 3:<a href="https://code.visualstudio.com/download"> VS Code</a>
<li>Optional Step 4: <a href="https://code.visualstudio.com/docs/datascience/jupyter-notebooks">VS Code setup</a>
<li>Optional Step 5 (Recommended way of organizing projects in Python):<a href="https://docs.python.org/3/library/venv.html"> Python virtual environment</a>
</ul>


<H5>Linux</H5>
<p1> Here we can just use our package manager to install and update things if they are not installed (should already be), and then use a python virtual environment with or without vscode. </p1>

<ul>
<li>Step 1: Python <a href="https://www.geeksforgeeks.org/how-to-install-python-in-ubuntu/"> (Ubunutu or apt-get example)</a> <a href="https://wiki.archlinux.org/title/Python"> (Arch or pacman example)</a>
<li>Step 2: <a href="https://jupyter.org/install">Jupyter Notebook</a>
<li>Optional Step 3:<a href="https://code.visualstudio.com/download"> VS Code</a>
<li>Optional Step 4: <a href="https://code.visualstudio.com/docs/datascience/jupyter-notebooks">VS Code setup</a>
<li>Optional Step 5 (Recommended way of organizing projects in Python):<a href="https://docs.python.org/3/library/venv.html"> Python virtual environment</a>
</ul>


<p1>Alternatively, one can use <a href="https://docs.anaconda.com/anaconda/install/"> Anaconda</a> as a package manager and work environment.</p1>


<H3>Qiskit Install and Account Creation</H3>

<p1> If your Python environment is setup correctly you should be able to use the following commands:
<code>
pip install qiskit qiskit-ibm-runtime qiskit[visualization] matplotlib</code>.
 If you have downloaded the whole repo you can also install from the *requirements.txt* file by using the following command with python <code>pip install -r requirements.txt</code> or the path to the requirements file.
</p1>

<p1>Here is the link to sign up for an account: <a href="https://www.ibm.com/quantum/pricing">IBM Quantum</a>. Follow the options for creating a free account labled as "Open Plan".</p1>

<p1>If you are having trouble you can follow this <a href="https://docs.quantum.ibm.com/guides/install-qiskit#local"> Qiskit IBM guide</a>.</p1>


<h3>Qiskit Code Assistant</h3>

<p1>IBM, as of the 9th of October 2024, has released the <a href=https://www.ibm.com/quantum/blog/qiskit-code-assistant>Qiskit Code Assistance</a>. This is an artifical intelligence (AI) or large language model (LLM) powered coding assistant tool that is compatible with Python .py or Jupyter .ipynb files. IBM has also released extensions for VS Code and Jupyter Lab. The LLM tool is powered by IBM's in house *granite-8b-qiskit*, which is based on their <a href=https://github.com/ibm-granite/granite-code-models>*granite-8b-code model*</a>. <a href=https://arxiv.org/abs/2405.19495>Here</a> is the paper written on the creation of this tool. This feature is currently in an experimental phase or preview release status and only available to Premium Plan users, so it will not be used here. IBM outlines all of this in on their <a href=https://docs.quantum.ibm.com/guides/qiskit-code-assistant#qiskit-code-assistant>documentation page</a> and goes into further detail.</p1>


<h3> Further Guide Content</h3>

<p1> Above, we have briefly covered resources for setting up an environment to run Python code and to use the Qiskit SDK. There are now several notebooks that follow the Qiskit *Hello World* guide with a small quantum circuit, *Hello World* with a large number of qubits, and a general example of setting up quantum teleportation.</p1>

<p1>The guides take advantage of text blocks describing what will be done in the following code blocks. The text blocks provide links to external resources such as IBM documentation, Python documentation, IBM guides (which include videos), and other resources that might be useful to a beginner. The code blocks are well commented and attempt to explain what each line is doing with in reason. If further clarification is needed on a line of code, it should be present before or after the code block where the confusing code is located.</p1>


<h3> Documents and Notebooks </h3>

<p1>
<ul>
<li><a href=/Notebooks/Environment_Setup.ipynb>Environment Setup Notebook</a>
<li><a href=/Notebooks/Qiskit_Hello_World.ipynb>Qiskit Hello World</a>
<li><a href=/Notebooks/Quantum_Teleportation.ipynb>Quantum Teleportation</a>
<li><a href=/Notebooks/Setup_and_Qiskit_Hello_World.ipynb>Setup and Qiskit Hello World</a>
<li><a href=/Citations.pdf>Citations</a>
</ul>
</p1>