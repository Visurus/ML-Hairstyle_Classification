# Hairstyle Classification
![Image](https://images.squarespace-cdn.com/content/v1/598954afcd39c3ced7441153/1548705184034-NB71CWFINFFY0NUS619Q/ke17ZwdGBToddI8pDm48kLPswmMOqQZ9-Q6KHLjvbpZ7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UTcpTqfU-ZEsztPyQLxhSSK-PhJjRDDFQG0l3_ZnmWi1QjT9byXZM3ISxo3y1NRptg/Hairtypechart+copy.jpg?format=2500w)

The dataset contains a sample 10000 images mined from Instagram 
and clustered based on the hairstyle they showcase.  
 
The variable `cluster`  represents the hairstyle cluster that the image has been assigned to by 
the visual recognition algorithm. 
 
Each row contains the variable `url` which is the link to the image and  the number of ​ likes 
together with the `comments` per image.  The `user_id`  is the unique id of the Instagram account 
from which the post comes and the variable  `id`  is the unique identifier associated with the post 
itself.

Each post contains the date(`date_unix`)  in unix format when the image was posted on 
Instagram and additionally the date has been converted to different formats (`date_week`->non-iso number of the week, `date_month`  -> the month, `date_formated` ->full date dd/mm/YY) partly 
for use in prior analyses. Feel free to convert that variable in a way that suits your analysis. 
 
Additionally a classifier `influencer_flag` was added to each of the images which have more than 
500 likes, flagging them as influencer posts.  
