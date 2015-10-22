# ruby_enterprise
Ruby Enterprise 1.8.7-2012.02 with patches to run on newer OSs. This is so legacy applications can update infrastructure.

You should sunset any application running Ruby 1.8.7 or upgrade it to use a more recent supported Ruby version.


## To install ruby-enterprise-2012.02

1. Clone this repo in the following manner:

  ```
  git clone git@github.com:bacrossland/ruby_enterprise.git ruby-enterprise-1.8.7-2012.02
  ```
or download the zip version, unpack it and rename the ruby_enterprise folder to ruby-enterprise-1.8.7-2012.02.

1. Use the installer and follow the directions.

  ```
  ./ruby-enterprise-1.8.7-2012.02/installer
  ```

## Tar for deployment

To tar this repo for deployment, do the following:

1. Clone this repo in the following manner:

  ```
  git clone git@github.com:bacrossland/ruby_enterprise.git ruby-enterprise-1.8.7-2012.02
  ```
or download the zip version, unpack it and rename the ruby_enterprise folder to ruby-enterprise-1.8.7-2012.02.

1. Tar the repo using the following command:

  ```
  tar -zcvf ruby-enterprise-1.8.7-2012.02.tar.gz ruby-enterprise-1.8.7-2012.02/
  ```

1. To unpack use the following command:

  ```
  tar -zxvf ruby-enterprise-1.8.7-2012.02.tar.gz
  ```


