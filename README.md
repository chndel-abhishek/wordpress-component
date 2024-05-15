#  Wordpress Component
This is the content management part in the wordpress 
## CICD 

```Github Actions ``` as CICD which will trigger when any push occur in this repository and its yaml located inside the ```.github/workflows/```.

## Coding Standards
In the CICD, I have:
```bash
-> Implemented PHPCS (PHP_CodeSniffer) for the WordPress component.
-> Configure PHPCS to enforce WordPress coding standards.
-> If the tests fails then pipeline will fail
```