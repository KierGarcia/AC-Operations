# Migration notes

Source recovered from the WordPress filesystem archive and database dump.

Important before canceling WordPress:

1. Deploy this static site to the chosen host.
2. Test all pages on desktop and mobile.
3. Confirm DNS points to the new static host.
4. Confirm email still works after DNS changes.
5. Only then cancel the WordPress.com Starter plan.

Security cleanup:

The database dump contained WordPress/plugin configuration. Do not upload the original database dump or full WordPress backup to a public GitHub repository. Only publish this cleaned static site folder.
