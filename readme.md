```
Read Before Complaining

Since i closed Unique Services store this project is not maintained anymore.
The last update works fine for all the frameworks, if you have 0 development knowledge please hire a dev before creating a stupid issue report.

Dispatch System For The MDT

https://github.com/i1An/unique-dispatch

1. Install SQL:

Inject database.sql Into your Database.

Make sure it all went in without errors.

If you are using esx framework make sure to inject this too:

ALTER TABLE `users`
	ADD COLUMN `pp` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `policemdtinfo` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `tags` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `gallery` LONGTEXT NULL DEFAULT ''
;

If you are using qbcore framework make sure to inject this too:

ALTER TABLE `players`
	ADD COLUMN `pp` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `policemdtinfo` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `tags` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `gallery` LONGTEXT NULL DEFAULT ''
;

If you are using pepe framework make sure to inject this too:

ALTER TABLE `characters_metadata`
	ADD COLUMN `pp` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `policemdtinfo` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `tags` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `gallery` LONGTEXT NULL DEFAULT ''
;

If you are using npbase framework make sure to inject this too:

ALTER TABLE `characters`
	ADD COLUMN `pp` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `policemdtinfo` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `tags` LONGTEXT NULL DEFAULT '',
	ADD COLUMN `gallery` LONGTEXT NULL DEFAULT ''
;
```
