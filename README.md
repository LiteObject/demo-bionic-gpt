# Demo Bionic-GPT

>BionicGPT is designed to be installed in your data center and then serve Generative AI to potentially hundreds of people via their browser.

>BionicGPT can run on modest hardware (16GB ram) and then scale into more powerful hardware when required. For example 70B running across multiple GPU cards.

## Installation (CPU)

### Copy the docker-compose file
    curl -O https://raw.githubusercontent.com/bionic-gpt/bionic-gpt/main/docker-compose/docker-compose.yml

When you run the given `curl` command, it will download the `docker-compose.yml` file from the provided URL and save it in the current directory with the same name.

### Run the docker-compose file
    docker-compose up

### Complete user registration

The first user to register with BionicGPT will become the system administrator. The information is kept local to your machine and your data is not sent anywhere.