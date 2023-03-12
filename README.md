# Replication package

The repository contains the replication pacakge for the paper "Understanding information diffusion about open-source projects on Twitter, HackerNews, and Reddit" in CHASE 2023.

## File  
replication_main_socialmedia_oss.Rmd (main replication pacakge)  
replication_validation.Rmd (robustness check package)

# Open dataset

The repository contains the open dataset for social media posts that mention open source projects in R and Python ecosystems.  

## File  
raw_data_repo2media.zip

## How to use  
Unzip "raw_data_repo2media.zip", and obtain two files "repo2parsed_social_media_list_com_Python_release.json" and "repo2parsed_social_media_list_com_R_release.json", which corresponds to projects in R and Python ecosystem apiece.

Each json file contains a dictionary, with the key being the project repo_slug (e.g. *mjskay/tidybayes*), and the value being a list of social media posts.
Each post was represented by a list of length four, with the meaning of each item shown below:  

item[0]: link to the social media post.  
item[1]: time when the post was created.  
item[2]: the platform where the post was on.  
item[3]: the corresponding project (same as the key).

