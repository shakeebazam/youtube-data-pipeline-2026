Bronze bucket = yt-shak-2026project-bronze
Silver bucket = yt-shak-2026project-silver
Gold bucket = yt-shak-2026project-gold

Script bucket = yt-shak-2026project-script

aws-cli-local acceskey = AKIA32BEM******** , +4aNmM5UQD0R+**********

SNS arn = arn:aws:sns:ap-south-1:811825121691:yt-data-pipeline-alerts-sns

Glue bronze table = yt-pipeline-bronze-glue-db
Glue silver table = yt-pipeline-silver-glue-db
Glue gold table = yt-pipeline-gold-glue-db


--bronze_database yt-pipeline-bronze-glue-db
--bronze_table raw_statistics    
--silver_bucket yt-shak-2026project-silver 
--silver_database yt-pipeline-silver-glue-db  
--silver_table clean_statistics            
--silver_path               


--silver_database yt-pipeline-silver-glue-db
--gold_bucket yt-shak-2026project-gold
--gold_database yt-pipeline-gold-glue-db