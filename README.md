# ChikurinRestaurant
This is a simple app that displays a single page with an image about a local business and contact information
This is the first project of Udacity NanoDegeree Android program.

The app utilizes a Relative Design with a single TextView and ImageView on the top and additional LinearLayout (Horizontal)
with 2 children LinearLayout (Vertical). The Vertical Layout on the left has a weight of 1 and the one on the right has the
weight of 4. This way the layout on the left can hold small image files that correspond to information displayed in layout
on the right. The layout on the left contains 4 ImageViews while the one on the right contains 4 TextViews. Height was manually
inputted for all views in both layouts so they all look aligned to each other.

Views in a RelativeLayout are positioned from top to bottom using android:layout_below"@id/name" attributes.
