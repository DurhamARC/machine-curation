# Liverpool biennial 2021 dataset

`LB2021_data.csv` - includes important metadata surrounding the Liverpool Biennial collection. This data is taken from the [LB2021 website](https://www.liverpoolbiennial2021.com/)
- 'artist' - artist name (from the web)
- 'featured_text' - text about the artwork extracted from the web - (preprocessed data, important for keywords_extraction) 
- 'img_url' - url to the image (from the web)
- 'data_caption' - text below the image (from the web, includes artist name, title and year)
- 'clean_title' - title after preprocessing - (important for generating images from titles)
- 'LB_web_artist_url' - link to artist page (from the web) 
- 'code' - id of artist (from the web, related to the artist web page) 
- 'path_to_original_image' - path to original image from root of repository. Note: the folders in `datasets/liverpool_biennial_2021/original_images` need to be unzipped in place for these paths to be correct.

The 50 artworks presented at LB2021 are zipped in three folders in `datasets/liverpool_biennial_2021/original_images`. These have been sourced from the [LB2021 website](https://www.liverpoolbiennial2021.com/) and permission has been granted for them to be uploaded to Git.
