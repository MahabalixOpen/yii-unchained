yii-unchained
=============

Extended versions of the Yii framework to include popular extensions such as yii-user,rights and so on.



INSTALLATION
------------
1. Migrate Yii Site and SQL database


Issues
------
1. Fix caps table names for Rights for compatibility on linux servers.


Changes
-------

2.Added Rights and changed Rights-> "class RWebUser extends CWebUser" -> "class RWebUser extends WebUser". This fixes login error.(WebUser was introduced by Yii-user)
1.Added Yii-User