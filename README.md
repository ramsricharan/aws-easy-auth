### Install AWS CLI
    Go to the following link to install the AWS CLI tools
    https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html

### Install aws-easy-auth
    To install and run aws-easy-auth on your machine you need to the following setup.

    1. Download the Executables. 
        Go to the aws-easy-auth repos releases to pick the latest version [here](https://github.com/ramsricharan/aws-easy-auth/releases). Then either download the executables manually or run the following command.

        ```wget https://github.com/ramsricharan/aws-easy-auth/archive/{RELEASE_TAG}.zip```

    2. Unzip the executables
        Now run the following command to unzip the executables.
        ``` unzip {RELEASE_TAG}.zip```

    3. Now move the executable to user's bin directory
        Use the following command to move the downloaded executable to user's bin directory.

        ```mv aws-easy-auth-{RELEASE_TAG}/aws-easy-auth /usr/local/bin```

    4. Finish
        To verify the installation, run the following command.
        ``` aws-easy-auth ```

