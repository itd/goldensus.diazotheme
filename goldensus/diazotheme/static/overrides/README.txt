Put the Plone templates you want to override in here.
Need to name the file template names with the complete
path to its original version.

For instance, to override colophon.pt from plone.app.layout,
knowing this template in a subfolder named viewlets,
you need to name the file in overrides:
   plone.app.layout.viewlets.colophon.pt.

Note:
 ZMI > portal_view_customizations
 ...is a handy way to find the template path.
