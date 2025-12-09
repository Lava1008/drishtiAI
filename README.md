This  project  presents  Drishti  designed  to  assist  visually  impaired  individuals  by  providing 
real-time  understanding  of  their  surroundings.  The  system  integrates  multiple 
technologies—  ESP32-CAM  streaming  ,  OCR-based  text  reading  ,  BLIP  image 
captioning  ,  CLIP-based  object  recognition  ,  and  voice  interaction  —to  deliver  accurate, 
fast, and natural feedback to the user. 
The  ESP32  camera  module  captures  live  video,  which  is  processed  using  advanced  machine 
learning  models  capable  of  reading  product  labels,  identifying  objects,  detecting  text, 
predicting  product  names,  and  describing  the  environment.  The  OCR  module  extracts 
readable  text  from  scenes,  while  BLIP  and  CLIP  models  generate  meaningful  image 
descriptions  and  object  classifications.  A  custom  product-detection  logic  further  enhances 
accuracy for packaged goods, identifying MRP, product type, expiry dates, and more. 
To  ensure  usability  for  visually  impaired  users,  the  system  supports  fully  voice  commands  , 
wake-word  detection,  and  text-to-speech  feedback.  The  terminal  interface  is  optimized  for 
blind  users,  providing  only  essential  spoken  responses  while  detailed  logs  are  saved  for 
analysis and debugging. 
Overall,  the  system  demonstrates  an  effective  fusion  of  machine  learning,  embedded 
computing,  and  accessibility  technologies,  resulting  in  an  affordable  and  practical  solution 
aimed at empowering visually impaired individuals in their daily activities. 


For using esp32 cam directly go to modules\camera\esp32_camera.py and paste the IP address of your esp32 webcam running int URL 
