WP workshop BRDC
=========

Extremely basic docker-compose setup for Wordpress.

**Includes:**

* docker-compose 3.3
* latest version of Wordpress
* mysql:latest
* data volume for db
* uploads.ini file to bump all the annoying default size restrictions
* mapping for wp-content

### Installation

Clone this repo. Create a wp-content folder

    git clone https://github.com/akkradet/wp-workshop && \
    cd wp-workshop && \
	mkdir wp-content0 && \
    mkdir wp-content1 && \
	mkdir wp-content2 && \
	mkdir wp-content3 && \
	mkdir wp-content4 && \
	mkdir wp-content5

### Run

    docker-compose up -d
