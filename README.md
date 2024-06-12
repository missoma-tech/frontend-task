# TASK:

Build a simple product page using the data in the JSON object.

The page must have the following functions:

    1. List all variants on product page using the JSON data
    2. Must be able to select a variant
    3. Replace the relevant variant information and imagery on selecting a variant
    4. On clicking "Add to Bag", log the selected variant id to the console

Important Information:

1. Fix the issues in the JSON
2. Use the provided example as a guide, but feel free to layout the page as you want - https://github.com/missoma-tech/frontend-task/blob/master/example-page-layout.jpg
3. The page should be responsive and fit on a mobile viewport
4. Send the task in a .zip with instructions on how to view in a browser
5. Avoid using any JS Frameworks like jQuery and try to use VanillaJS
6. Check the JSON data for errors
7. Don't spend more than 2 hours on this task, if you have questions, please contact your recruiter
8. Be prepared talk about your implementation choices
9. You do not need to create a Shopify website to complete this task. A simple one-pager will suffice.
   

# Product Data

```
{
  "id": 1,
  "title": "Engravable Square Locket Clip-On Pendant",
  "description": "This locket clip-on pendant features a rainbow moonstone at the centre and bevelled square shape with rope edge detail. It opens to fit a small photo and can be engraved on the back. Clip it on to any of our customisable chains to add the ultimate personal touch to your necklace layers.",
  "available": false,
  "price": 10500,
  "variants": [
    {
      "id": 123,
      "name": "Engravable Square Locket Clip-On Pendant - 18ct Gold Plated/Rainbow Moonstone",
      "title": "18ct Gold Plated/Rainbow Moonstone",
      "available": true,
      "price": 10500,
      "featured_image": "https://cdn.shopify.com/s/files/1/0286/4703/0828/products/engravable-square-locket-clip-on-pendant-necklaces-missoma-18ct-gold-platedrainbow-moonstone-221896.jpg?v=1622577088"
      "option1": "18ct Gold Plated",
      "option2": "Rainbow Moonstone",
      "option3": null
    }
    {
      "id": 456,
      "name": "Engravable Square Locket Clip-On Pendant - Silver Plated/Pink Pave",
      "title": "Silver Plated/Pink Pave",
      "available" false,
      "price": 9500,
      "featured_image": "https://cdn.shopify.com/s/files/1/0286/4703/0828/products/engravable-square-locket-clip-on-pendant-necklaces-missoma-silver-platedrainbow-moonstone-182310.jpg?v=1622579310",
      "option1": "Silver Plated",
      "option2": "Pink Pave",
      "option3": null
    }
    {
      "id": 789,
      "name": "Engravable Square Locket Clip-On Pendant - 18ct Gold Plated/Amazonite",
      "title": "18ct Gold Plated/Amazonite",
      "available": true,
      "price": 10100,
      "featured_image": "https://cdn.shopify.com/s/files/1/0286/4703/0828/products/engravable-square-locket-clip-on-pendant-necklaces-missoma-18ct-gold-platedrainbow-moonstone-221896.jpg?v=1622577088",
      "option1": "18ct Gold Plated",
      "option2": "Amazonite",
      "option3": null
    }
  ]
}
```
