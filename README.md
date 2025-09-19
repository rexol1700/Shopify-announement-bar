# Shopify-announement-bar
Modifyable announcement bar

This is not perfect but it gives a very good ilusion of hiding away as you scroll down

1.Put the code from the file in ths reposatory somewhere at the top of your header. right under links to resources and schema/liquid


2. Sett up Metafields 

Go to Settings → Metafields og create following:
For Pages:

Namespace: custom
Key: announcement_items
Type: Multi-line text
Description: Kommaseparerte announcement items

Namespace: custom  
Key: announcement_bg
Type: Color
Description: Bakgrunnsfarge for announcement

Namespace: custom
Key: announcement_text_color  
Type: Color
Description: Tekstfarge for announcement

Namespace: custom
Key: hide_announcement
Type: Boolean
Description: Skjul announcement bar på denne siden

For Products:

(Same metafields as above)

For Collections:

(Same metafields as above)


