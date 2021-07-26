# Liverpool biennial 2021 dataset

`LB2021_data.csv` - includes data from the LB2021 web (https://www.liverpoolbiennial2021.com/) and new (generated/preprocessed) data:
- 'artist' - artist name (from the web)
- 'artist_url' - link to artist page (from the web) 
- 'code' - id of artist (from the web, related to the artist web page) 
- 'img_url' - url to the image (from the web)
- 'data_caption' - text below the image (from the web, includes artist name, title and year)
- 'title' - original artwork title (from the web)
- 'clean_title' - title after preprocessing - (important for generating images from titles)
- 'img_path' - path to the original artwork image (currently specified for Eva's local machine)
- 'generated_img_path' - path to the (from title) generated image on Eva's local machine
- 'featured_text' - text about the artwork extracted from the web - (preprocessed data, important for keywords_extraction) 
- 'keywords' - the keywords extracted from the featured text 
- 'flickr_caption' - the caption generated using VLP model (result of runing the captioning model, important for creating attention maps)
