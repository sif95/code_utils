# code_utils
my code utils
Ceres Solver 1.14.0 is required to build code_utils

Thanks to @gaowwnliang for the proper Ceres Solver install:
Steps to install Ceres:</p>
<div class="highlight highlight-source-shell"><pre>sudo apt-get install libgoogle-glog-dev
sudo apt-get install libatlas-base-dev
sudo apt-get install libeigen3-dev</pre></div>
<p>Download the following file:</p>
<pre><code>http://ceres-solver.org/ceres-solver-1.14.0.tar.gz
</code></pre>
<p>Execute:</p>
<div class="highlight highlight-source-shell"><pre>tar zxf ceres-solver-1.14.0.tar.gz
mkdir ceres-bin
<span class="pl-c1">cd</span> ceres-bin
cmake ../ceres-solver-1.14.0
make -j3
make install</pre>
<pre><code>
sudo apt-get install libdw-dev
 </pre> 
<p>Use the following commands to download and compile the package.</p>
<pre><code>cd ~/catkin_ws/src
git clone https://github.com/Rotoslider/code_utils
cd ..
catkin_make
</code></pre>
