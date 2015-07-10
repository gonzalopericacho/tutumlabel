# tutumtag

Image that inserts in the Dockerfile a JSON version of the tutum.yml

## Usage

    docker run -v $(pwd):/image tutum/tutumtag

Note that for proper working user should be in the path where the Dockerfile and the tututm.yml are. In addition, the user can change $(pwd) with the absolute path where the files are.