# gcp-cheatsheet
Google Cloud Platform CheetSheet




|	cmd	|	info	|
|	:----	|	----	|
|	***`gcloud`***	|	`Manage Google Cloud Platform resources and developer workflow`	|
|	gcloud config list	|	View your current gcp project info/details	|
|	gcloud config set project [project]	|	Set/Change active project	|
|	gcloud projects list	|	List of all your gcp projects	|
|	gcloud components list	|	List of components available through the Google Cloud SDK	|
|	gcloud components install	|	Installs SDK component	|
|	gcloud components update	|	Updates SDK component	|
|	gcloud components remove	|	Removes SDK component	|
|	gcloud compute regions list	|	Returns list of available regions	|
|		|		|
|	***`gsutil`***	|		|
|	gsutil mb -c regional -l asia-east1 gs://my-new-awesome-bucket	|	Create new Cloud Storage Bucket	|
|	gsutil ls	|	List all your buckets	|
|	gsutil cp	|	Copy objects	|
|	gsutil lifecycle get gs://[your bucket]	|	Returns lifecycle of your bucket (for example delete files in the bucket after 1 month)	|
|	gsutil acl get gs://[your_bucket]	|		|
|	gsutil versioning set on gs://[your bucket]	|	Versioning on bucket.	|
|	gsutil rsync -r . gs://[your bucket]	|	The gsutil rsync command makes the contents under dst_url the same as the contents under src_url	|
