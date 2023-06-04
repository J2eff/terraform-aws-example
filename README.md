# terraform-aws-example

## Prerequisites

Install tfenv

### on macos
```
brew install tfenv
```

### on ubuntu
```
git clone https://github.com/tfutils/tfenv.git ~/.tfenv
echo 'export PATH="$HOME/.tfenv/bin:$PATH"' >> ~/.bash_profile
sudo ln -s ~/.tfenv/bin/* /usr/local/bin
```

## Configure Aws profile

```
aws configure --profile jeff ( profile name )
````
````
AWS Access Key ID [None]: ********
AWS Secret Access Key [None]: ********
Default region name [None]: ap-northeast-2
Default output format [None]: json
```
