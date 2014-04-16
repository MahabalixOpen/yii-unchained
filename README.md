Yii-Unchained
=============================


INSTALLATION
------------
1. Migrate Yii Site and SQL database


Issues
------
1. Fix caps table names for Rights for compatibility on linux servers. ### Wrote renamer.sql for it
2. Write Audit Trail page that shows which models have/do not have audit trail
3. Is a merger of Cmenu and YiiSmartmenu possible?


Changes
-------
8. Added edit area extension to yii-unchained(rich text editor) http://www.yiiframework.com/extension/editarea/
7. Added unchained_resources dir that contains all software added.
6. Added leftsidebar and rightsidebar to extensions (edited /layouts/main.php to add some comments)
5. Installed YiiSmartMenu(edited /layouts/main.php to add some comments)
4. Installed Yiistrap and YiiWheels
3. Installed the original http://www.yiiframework.com/extension/audittrail/, choosing over this one - https://github.com/Sammaye/audittrail
2.Added Rights and changed Rights-> "class RWebUser extends CWebUser" -> "class RWebUser extends WebUser". This fixes login error.(WebUser was introduced by Yii-user)
1.Added Yii-User