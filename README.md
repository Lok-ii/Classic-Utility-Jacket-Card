# Classic-Utility-Jacket-Card

<h2>Hosted Link:- https://lok-ii.github.io/Classic-Utility-Jacket-Card/dist/index.html</h2>
<br>
<br>

# Description:

![Screenshot 2023-09-01 144711](https://github.com/Lok-ii/Classic-Utility-Jacket-Card/assets/129180844/88ebc048-2e8b-4d51-a95c-57cd27833abb)
![Screenshot 2023-09-01 144752](https://github.com/Lok-ii/Classic-Utility-Jacket-Card/assets/129180844/ecbeaf6d-e93d-4d47-b46d-f4771e1c8bc0)

    Main Section:

        The entire content of the page is enclosed in a <section> element with the class font-sans, which sets the font family.
        It uses flexbox (flex) for layout control.
        The content is centered both horizontally and vertically on the screen (items-center, justify-center).
    
    Main Container:
        
        Within the <section>, there is a <div> with the class main-container. This container holds the product information.
        It uses flexbox to control the layout for different screen sizes (flex-col, sm:flex-row).
        It's a rounded, shadowed container with a maximum width (max-w-xl) and a height that adapts based on the screen size (h-[90%], sm:h-64).
        The sm:w-[45%] and sm:h-64 classes control the width and height for small screens.
        
    Product Image:
        
        On the left side of the container, there's a div with the class shoe that holds the product image.
        The image is centered and overflows hidden if it's too large.
    
    Product Details:
        
        On the right side of the container, there's a div that contains the product details.
        The details include the product name, price, availability, size options, and buttons to buy or add to the bag.
        It uses a flex layout with items aligned to the start (items-start).
        There's also a horizontal rule (<hr>) under the product details.
    
    Size Options:
        
        Size options are displayed as clickable boxes (div) with sizes like XS, S, M, L, XL.
        These boxes change color and text color when hovered over (hover:bg-black, hover:text-white).
    
    Purchase Buttons:
        
        There are three buttons: "Buy Now," "Add to Bag," and a heart icon.
        These buttons have different styles and widths based on the screen size.
        The heart icon is from Font Awesome.
    
    Shipping Information:
        
        At the bottom of the product details, there's a paragraph with information about free shipping.
