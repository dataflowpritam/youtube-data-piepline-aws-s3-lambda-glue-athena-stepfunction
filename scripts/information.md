Bronze Bucket Name - yt-data-pipeline-bronzee-ap-south-1-dev 
Silver Bucket Name - yt-data-pipeline-silverrr-ap-south-1-dev 
Gold Bucket Name - yt-data-pipeline-golddd-ap-south-1-dev 

Script Bucket - yt-data-pipeline-scriptss-ap-south-1-dev


SNS ARN - arn:aws:sns:ap-south-1:325844081876:yt-data-pipeline-alerts-dev:816868e6-0e87-4d09-bc93-61508a09727c



Glue Bronze - yt_pipeline_bronze_dev
Glue Gold - yt_pipeline_gold_dev
Glue Silver - yt_pipeline_silver_dev



--bronze_database yt_pipeline_bronze_dev
--bronze_table raw_statistics
--silver_bucket yt-data-pipeline-silverrr-ap-south-1-dev
--silver_database yt_pipeline_silver_dev
--silver_table clean_statistics


--silver_database yt_pipeline_silver_dev
--gold_bucket yt-data-pipeline-golddd-ap-south-1-dev
--gold_database yt_pipeline_gold_dev
