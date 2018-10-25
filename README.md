# Wordpress Scaffolding

:building_construction: :construction: :construction_worker: A kick starter project structure for wordpress.

## Note

- The wordpress core is only registered as git submodule in ```/wordpress/```, 

- Current git submodule wordpress version is 4.9.8.

## Supported Web Server

- Apache

## Requirement(s)

- PHP version from 5.6.* up to latest.

- You can also check the latest wordpress requirements: <https://wordpress.org/about/requirements/>

## Install

- Recommended to install the project via Composer. Use the command below to install the package:

```txt
composer create-project lorddashme/wordpress-scaffolding <your-project-name>
```

## Usage

- Add what ever wordpress version you want to use in ```/wordpress/```.

  - You can check the wordpress download releases here: https://wordpress.org/download/releases/
  
- <b>Optional:</b> If you are lazy to install wordpress on your own, you can follow the instruction below. 
  
  - To install specific wordpress version you can use the command below, but make sure you are in the root directory of you project:

  ```text
  php wordpress-scaffolding install <your-wordpress-version>
  ```

- Copy and rename the default file(s):

  - ```wp-config-sample.php``` > ```wp-config.php``` - To enable the wordpress config file.

  - For apache only: ```htaccess-sample``` > ```.htaccess``` - To enable some security and override the apache host setup.

## License

- This package is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
