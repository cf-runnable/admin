This is an administrative repo to keep track of scripts and such to manage my runnables.

## .setup

Keep this bash script in the web root.  Call it with the name of a repo in cf-runnable.  It will clear out the web root save itself and WEB-INF and then clone that repo into the web root by way of a tmp folder (since you can't actually clone into a non-empty folder)

Usage:

$> ./.setup CFML_Templating_With_Tags