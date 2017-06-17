# suppose you are in the Root_Dir of caffe_ssd
1. change to ./data/data-USA
modify create_list.sh and creat_data.sh where necessary
such as "root_dir", "for dataset in trainval3 test", "data_root_dir", "dataset_name"
"root_dir" and "data_root_dir" is the directory where you put your Caltech Dataset in.
For more details, you can just look convert_annoset.cpp, io.cpp(function::ReadTxtToAnnotatedDatum) for help.

2. change to ./examples/ssd
modify ssd_caltech.py ssd_caltech_webcam.py where necessary
then, you could just run `ssd_caltech.py` according the normal process of ssd.

