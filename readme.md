# phing-build

## Shell Aliases

Command           | Description
------------------|-------------------------------------------------------
p [targets]       | Alias to run build script
l                 | Run log tail
a                 | Restart Apache
w                 | Navigate to projects dir
b                 | List of aliases: open ~/.bash_profile, apply aliases 
gs                | Git Status
gc                | Git Commit
ga                | Git Add

## Build with Phing

* Navigate to project
    
        cd /var/www/html/project.dev/
    
* Run build
    
        p
    
* Import database

        p import-db

Target                  | Description
------------------------|-------------------------------------------------------
config-typo3            |
config-neos             |
config-magento          |
backup                  |
backup-db               |
backup-media            |
backup-magento-log      |
backup-typo3-log        |
reset-settings          |
install                 |
deploy-full             |
deploy-tar              |
deploy-db               |
deploy-media-symlink    |
deploy-magento          |
deploy-sync             |
deploy-db-no-delete     |
deploy-media-direct     |
deploy                  |
deploy-code             |
server-setup            |
htaccess                |
deploy-docs             |
symlink                 |
deploy-upload           |
clean-typo3-symlink     |
clean-neos-direct       |
clean-typo3-direct      |
clean-magento-direct    |
clean-magento-symlink   |
import-db               |
install-typo3           |
typo3-clear-cache       |
install-magento         |
dist                    |
server-cleanup          |

Test Targets            | Description
------------------------|-------------------------------------------------------
test                    | Run phpcs, phpmd, phploc, phpcpd, pdepend
phpcs                   | 
phpmd                   |
phploc                  |
phpcpd                  |
pdepend                 |
phpunit                 |
casperjs                |

Service Targets         | Description
------------------------|-------------------------------------------------------
-load-properties        |
-setup-dirs             |
-clean-build            |
-load-properties-backup |

## Support

If you have any issues with this extension, open an issue on [GitHub](https://github.com/kirchbergerknorr/phing-build/issues).

## Contribution

Any contribution is highly appreciated. The best way to contribute code is to open a [pull request on GitHub](https://help.github.com/articles/using-pull-requests).

## License

[OSL - Open Software Licence 3.0](http://opensource.org/licenses/osl-3.0.php)