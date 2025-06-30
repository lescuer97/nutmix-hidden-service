# Nutmix-hidden-service

## Set-up Instructions

Follow these steps to get the Nutmix Hidden Service running on your local machine:

### 1. Clone the repository

```bash
git clone https://github.com/lescuer97/nutmix-hidden-service
cd nutmix-hidden-service
```

### 2. Set up the nutmix repository

```bash
git submodule sync --recursive .
```
### 2.1 Set up the .env file

Setup your .env file inside the nutmix repo. You can follow the env.example file.

```bash
cd nutmix
```

### 3. Build and deploy the Hidden Service

```bash
cd ..
bash start.sh
```

### 4. Access the Hidden Service

Once everything is set up, the Hidden Service will be running on the outputted `.onion` address.

Example output: `z64bvbz2niptamub2lzqnyyuycmsdokkffpak5x5uddsyd427dx7qqad.onion`

## Update Instructions

Follow these steps to update your deployment to the latest version of nutmix:

### 1. Pull the latest changes

```bash
cd nutmix-hidden-service
cd nutmix
git pull
```
### 2. Rebuild and redoply the Hidden Service

```bash
cd ..
bash start.sh
```
