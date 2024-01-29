To setup and run ,following steps need to be done.

Install Docker
To install Docker, please follow the instructions at this link.

Download AidUI docker image by executing the following command:
docker pull smhasanmansur/aidui-img
Run the container by executing the following command:
docker run -it smhasanmansur/aidui-img
Use following command to move to the root directory of AidUI:
cd AidUI/
Execute the following command to run AidUI
./run_dp_detection.sh
You should see the following prompt:
turn on evaluation mode? answer with y/n
Type y and press ENTER
The process usually takes around 1.5~2 hours

Once the process is complete, we can expect the following output files in the directory AidUI/output/

contains 162 web and 339 mobile screenshots depicting 301 DP and 243 Non-DP instances.
Trainig Data set is available here -> https://www.dropbox.com/s/s1mihip6eupspir/AidUI-Object-Detection-Dataset-Master.tar.gz?dl=0
