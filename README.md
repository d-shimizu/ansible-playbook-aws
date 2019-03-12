---
 
## Description

## Requirement

* Ansible 2.5
* pip module
  * boto
  * boto3
  * botocore
* AWS Access Key & AWS Secret Key

## Usage

```
export AWS_ACCESS_KEY_ID=xxxxxxxxxxxxxxxx
export AWS_SECRET_ACCESS_KEY=xxxxxxxxxxxxxxx
```
or 
```
aws configure
```

```
ansible-playbook -i hosts aws.yml
```

* Ubuntu 16.04 and later
```
ansible-playbook -i hosts aws.yml  --extra-vars "ansible_python_interpreter=/usr/bin/python3"
```
 
## Licence

## Author
 
 * [daisukeshimizu](https://github.com/daisukeshimizu)

