# Orthanc for experiment

## How to start
1. Start the services using Docker Compose:
    ```sh
    $ docker-compose up -d
    ```
2. Access the Orthanc web interface to upload DICOM files:
    - URL: [http://localhost:8042/app/explorer.html#upload](http://localhost:8042/app/explorer.html#upload)
    - Note: Data will be lost when you remove the container because I have not yet implemented Docker volumes.


## Orthanc Resources
* setup sample: https://github.com/orthanc-server/orthanc-setup-samples
* Orthanc Book: https://orthanc.uclouvain.be/book/index.html

## Orthanc.json
* configuration file: https://orthanc.uclouvain.be/hg/orthanc/file/Orthanc-1.12.6/OrthancServer/Resources/Configuration.json/
