# Multi-Objective-Routing

In this project, an implementation of a multi-objective routing approach is provided.
Using the estimated routing time and the estimated dangerousness as objectives, potential routings are depicted on a map of the city of Paris. Through this approach, weight emphasis selection is supported so that the user could define the weight percentage of each objective for the estimated routing. 
The algorithm can be executed up to a maximum of 4 query levels achieving low overall execution time in constrast to other state of the art multi-objective optimization routing techniques.
 
The code is distributed for academic and non-commercial use.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
 
## OS - System Information

This code was deployed using Windows 10 Home x64 operating system - Processor Intel Core i7-9750H CPU @ 2,6GHz - RAM 32 GB
 
## Prerequisites

Python 3.7

Microsoft Visual C++ Redistributables (2010, 2012, 2013, 2015-2019)
 
## Instructions:

### Installation

### Create a virtual environment (optional step)

python -m venv mosp-env

mosp-env\Scripts\activate.bat

### Install the required packages

python -m pip install GDAL-3.1.4-cp37-cp37m-win_amd64.whl

python -m pip install Fiona-1.8.18-cp37-cp37m-win_amd64.whl

python -m pip install -r requirements.txt

pip install ipykernel

python -m ipykernel install --user --name mosp-env

pip install notebook
 
### Run the algorithm

jupyter notebook
 
 
 
 
GDAL and Fiona .whl files were downloaded from:
https://www.lfd.uci.edu/~gohlke/pythonlibs/