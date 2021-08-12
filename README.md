test img :


./darknet detector demo build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg backup/yolov4-tiny-obj_final.weights -ext_output data/take_note.jpg

./darknet detector test build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg backup/yolov4-tiny-obj_final.weights data/take_note.jpg -out_filename writeTT.jpg

./darknet detector demo build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg backup/yolov4-tiny-obj_final.weights data/write01.avi -out_filename data/res.avi

./darknet detector test build/darknet/x64/data/try.data build/darknet/x64/yt4_try.cfg backup/yt4_try_final.weights -dont_show



./darknet detector train build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg build/darknet/x64/yolov4-tiny.conv.29 -dont_show

train :


./darknet detector train build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg build/darknet/x64/yolov4-tiny.conv.29 -map

./darknet detector train build/darknet/x64/data/try.data build/darknet/x64/yt4_try.cfg build/darknet/x64/yolov4-tiny.conv.29 -dont_show

./darknet detector train build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg build/darknet/x64/yolov4-tiny.conv.29 -dont_show


valid :




./darknet detector map build/darknet/x64/data/stanford.data build/darknet/x64/yolov4-tiny-obj.cfg backup/yolov4-tiny-obj_40000.weights



./darknet detector map build/darknet/x64/data/try.data build/darknet/x64/yt4_try.cfg backup/yt4_try_final.weights 

