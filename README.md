# ckanext-predataset
This extension allows us to select a data set that will be the basis for creating a new dataset

# Development Installation 
To install ckanext-predataset:

	1. Install ckanext-predataset.

		git clone https://github.com/inia-es/ckanext-predataset.git
		cd ckanext-predataset
		python setup.py develop
		pip install -r dev-requirements.txt

	2. Add predataset to the ckan.plugins setting in your CKAN config file (by default the config file is located at /etc/ckan/default production.ini)

	3. Restart CKAN. For example if you've deployed CKAN with Apache on Ubuntu: sudo service apache2 reload

