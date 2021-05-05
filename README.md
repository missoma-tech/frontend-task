# TASK:

Build a simple product page using the data in the JSON object.

The page must have the following functions:

    1. List all variants on product page
    2. Must be able to select a variant
    3. Replace the relevant variant information and imagery on selecting a variant
    4. On clicking "Add to Bag", log the selected variant id to the console

Important Information:
1. Fix the issues in the JSON 
2. Use the provided example as a guide, but feel free to layout the page as you want - https://github.com/missoma-tech/frontend-task/blob/master/example-page-layout.jpg
3. The page should be responsive and fit on a mobile viewport
4. Send the task in a .zip with instructions on how to view in a browser
5. Don't spend more than 2 hours on this task, if you have questions, please contact your recruiter
6. Be prepared talk about your implementation choices


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
      "featured_image": "https://cdn.shopify.com/s/files/1/0280/4603/3028/products/gold-moonstone-square-locket-clip-on-pendant-necklaces-missoma-625053_41097d42-1792-42ce-8c16-085698882ab7_700x.jpg?v=1618498015",
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
      "featured_image": "https://cdn.shopify.com/s/files/1/0280/4603/3028/products/silver-moonstone-square-locket-clip-on-pendant-necklaces-missoma-932830_7a6f661f-ffa8-48cb-a5e3-e9caf285aadb_700x.jpg?v=1618498015",
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
        "featured_image": "https://cdn.shopify.com/s/files/1/0280/4603/3028/products/gold-moonstone-square-locket-clip-on-pendant-necklaces-missoma-158039_96aa87ab-ed42-49c6-86c0-e85432c82f13_1600x.jpg?v=1618498015",
        "option1": "18ct Gold Plated",
        "option2": "Amazonite",
        "option3": null
      }
  ]
}
```
