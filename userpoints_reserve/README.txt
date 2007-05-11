Author: Mike Smullin http://mikesmullin.com

INSTALLATION

1. Extract to the /modules/userpoints/contrib directory.
2. Enable in Administer > Modules (admin/build/modules).
3. Configure in Administer > User Points settings (admin/settings/userpoints).

IMPORTANT! IMPORTANTE! WICHTIG!

You'll need to modify the /userpoints/contrib/userpoints_ecommerce/userpoints_ecommerce.module
to remove the maxlength of the field titled "!Points used in payment (for every dollar)".
Currently it is limited to 5 digits, and this is not enough in many cases.

As of this version, the part you need to remove is in userpoints_ecommerce.module on line 62.

That's it!
