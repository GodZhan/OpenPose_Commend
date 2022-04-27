# OpenPose Commeds

## run images

```
bin\OpenPoseDemo.exe --image_dir folodername/
```

## run images (Output)

```
bin\OpenPoseDemo.exe --image_dir folodername/ --write_images output_folodername
```

* if `output_folodername` don't exist,system will build one.

## run video

```
bin\OpenPoseDemo.exe --video folodername/filename
```

## run video (Output)

```
bin\OpenPoseDemo.exe --video folodername/filename --write_video output_folodername/output_filemname
```

* The `output_folodername` most exist

* filename ends with `.avi`

## run video (Output json with part_candidates)

```
bin\OpenPoseDemo.exe --video folodername/filename --part_candidates --write_json output_folodername/output_filename
```

* `output_filename` ends with `.json`

* The final result will be a foloder,each frame equal to a json file

## Scale part_candidates range 

* Range [0~1]

```
bin\OpenPoseDemo.exe --video folodername/filename --keypoint_scale 3 --part_candidates --write_json output_folodername/output_filename
```

* Range [-1~1]

```
bin\OpenPoseDemo.exe --video folodername/filename --keypoint_scale 4 --part_candidates --write_json output_folodername/output_filename
```

## run camera

```
bin\OpenPoseDemo.exe --camera 0
```

## run camera (output)

```
bin\OpenPoseDemo.exe --camera 0 --write_video output_folodername/output_filename
```

* `output_filename` ends with `.avi`