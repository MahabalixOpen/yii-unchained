yii-unchained
=============

Extended versions of the Yii framework to include popular extensions such as yii-user,rights and so on.




INSTALLATION
------------
1. Migrate Yii Site and SQL database


Issues
------
1. Fix caps table names for Rights for compatibility on linux servers. ### Wrote renamer.sql for it
2. Write Audit Trail page that shows which models have/do not have audit trail


Changes
-------
4. Installed YiiStrap and YiiWheels
3. Installed the original http://www.yiiframework.com/extension/audittrail/, choosing over this one - https://github.com/Sammaye/audittrail
2.Added Rights and changed Rights-> "class RWebUser extends CWebUser" -> "class RWebUser extends WebUser". This fixes login error.(WebUser was introduced by Yii-user)
1.Added Yii-User