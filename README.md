# Megamart-
PROJECT NAME: MegaMart

Complete E-Commerce Marketplace Website Development

Act as a senior full-stack developer, UI/UX designer, database architect, and e-commerce platform engineer.

Build a complete, professional, responsive, production-oriented Indian e-commerce marketplace named MegaMart.

MegaMart should provide a premium shopping experience inspired by the usability and feature depth of major Indian e-commerce platforms such as Flipkart and Amazon, but it must have its own original branding, visual identity, layouts, icons, graphics, and user experience. Do not copy their proprietary assets, logos, exact page designs, or product content.

TAGLINE:
"Everything You Need, All in One Place."

==================================================

1. BRANDING AND DESIGN SYSTEM
   ==================================================

Brand Name: MegaMart

Design Direction:

- Professional Indian e-commerce marketplace.
- Blue and yellow primary color combination.
- White backgrounds with light grey sections.
- Modern, clean, premium shopping interface.
- Product-focused design.
- Smooth animations and interactions.
- Attractive promotional banners.
- Professional typography.
- Responsive layouts for mobile, tablet and desktop.

Suggested Colors:

- Primary Blue: #1463D9
- Dark Blue: #073B8C
- Accent Yellow: #FFD43B
- Background: #F5F7FA
- White: #FFFFFF
- Main Text: #172033
- Success Green: #159447

Create an original MegaMart logo using a shopping bag/cart concept.

The website must look professional on Android phones as well as desktop browsers.

==================================================
2. TECHNOLOGY STACK

Frontend:

- HTML5
- CSS3
- JavaScript (ES6+)
- Responsive CSS
- Modular and reusable JavaScript components

Backend:

- Supabase

Database:

- Supabase PostgreSQL

Authentication:

- Supabase Auth
- Email and password
- Google login
- Password reset
- Email verification

Image Storage:

- Supabase Storage

Hosting:

- GitHub Pages

Payments:

- Razorpay integration
- UPI
- Cards
- Net Banking
- Cash on Delivery

Important:

- Never expose Supabase service_role keys or Razorpay secret keys in frontend code.
- Use secure Supabase Edge Functions for privileged operations.
- Configure Row Level Security (RLS) on all sensitive database tables.
- Do not use fake payment success responses.

==================================================
3. WEBSITE HEADER AND NAVIGATION

Create a professional shopping header containing:

- MegaMart logo
- Large product search bar
- Search button
- Login / Account
- Become a Seller
- Wishlist
- Shopping Cart
- Notifications

Desktop:

- Full-width navigation.
- Category navigation below the main header.
- Sticky header while scrolling.

Mobile:

- Compact responsive header.
- Search bar.
- Mobile-friendly navigation.
- Fixed bottom navigation.

Bottom navigation:

1. Home
2. Categories
3. Wishlist
4. Account
5. Cart

==================================================
4. HOMEPAGE

Create a complete homepage with:

A. Promotional Hero Banner

- Large promotional slider.
- Festival sale banners.
- Discount offers.
- Shop Now buttons.
- Previous and next slider controls.
- Automatic sliding with pause controls.

B. Product Categories

Create categories:

- Mobiles
- Electronics
- Fashion
- Men's Fashion
- Women's Fashion
- Kids
- Home & Furniture
- Appliances
- Beauty & Personal Care
- Grocery
- Sports & Fitness
- Books
- Toys
- Automotive
- Accessories

C. Deals of the Day

- Product images.
- Product name.
- Original price.
- Discounted price.
- Discount percentage.
- Rating.
- Add to Cart.
- View All.

D. Top Offers

E. Best of Electronics

F. Best of Mobiles

G. Fashion Deals

H. Home & Kitchen

I. Recommended Products

J. Recently Viewed Products

K. Trending Products

L. Best Sellers

All homepage sections must retrieve real product information from Supabase.

Do not permanently hardcode sample products into production sections.

==================================================
5. PRODUCT LISTING PAGE

Create a professional product listing page.

Features:

- Product grid.
- Product cards.
- Product images.
- Product name.
- Brand.
- Price.
- Original price.
- Discount percentage.
- Rating and review count.
- Availability.
- Wishlist button.
- Add to Cart button.

Filters:

- Category
- Brand
- Minimum and maximum price
- Customer rating
- Discount
- Availability
- Color
- Size
- Product specifications

Sorting:

- Popularity
- Price: Low to High
- Price: High to Low
- Newest First
- Highest Rated
- Best Discount

Include pagination or efficient loading.

==================================================
6. PRODUCT DETAILS PAGE

Every product must have its own dynamic details page.

Display:

- Multiple product images.
- Image gallery.
- Product title.
- Brand.
- Product price.
- Original price.
- Discount.
- Ratings.
- Reviews.
- Product description.
- Specifications.
- Available colors.
- Available sizes.
- Stock availability.
- Delivery PIN code checker.
- Estimated delivery date.
- Quantity selector.
- Add to Cart.
- Buy Now.
- Add to Wishlist.

Also include:

- Product highlights.
- Similar products.
- Related products.
- Frequently bought together.
- Customer questions and answers.

==================================================
7. SEARCH SYSTEM

Implement a working search system.

Requirements:

- Search products by name.
- Search by brand.
- Search by category.
- Search suggestions.
- Recent searches.
- Popular searches.
- Search results page.
- No results found page.
- Filters and sorting on search results.

Search must use actual Supabase product data.

==================================================
8. USER AUTHENTICATION

Create:

- Login page.
- Registration page.
- Google authentication.
- Email/password authentication.
- Forgot password.
- Reset password.
- Email verification.
- Logout.

User profile:

- Full name.
- Email.
- Mobile number.
- Profile photo.
- Saved addresses.
- PIN code.
- City.
- State.

Allow users to edit and save their profile.

Protect private pages and user information.

==================================================
9. SHOPPING CART

Implement a fully functional cart.

Features:

- Add product.
- Remove product.
- Increase quantity.
- Decrease quantity.
- Product stock validation.
- Price calculation.
- Discount calculation.
- Delivery charges.
- Coupon application.
- Cart total.
- Proceed to Checkout.

Cart must persist across login sessions using a secure and reliable database-backed approach.

==================================================
10. WISHLIST

Features:

- Add to wishlist.
- Remove from wishlist.
- View wishlist.
- Move wishlist product to cart.
- Persistent wishlist for logged-in users.

==================================================
11. CHECKOUT AND ORDERS

Checkout steps:

1. Login verification.
2. Delivery address.
3. Order summary.
4. Coupon application.
5. Payment selection.
6. Order confirmation.

Payment options:

- UPI
- Credit Card
- Debit Card
- Net Banking
- Cash on Delivery.

Integrate Razorpay through secure backend functions.

Order management:

- Unique order ID.
- Customer details.
- Product details.
- Quantity.
- Price.
- Delivery address.
- Payment method.
- Payment status.
- Order status.
- Order date.

Order statuses:

- Order Placed
- Confirmed
- Packed
- Shipped
- Out for Delivery
- Delivered
- Cancelled
- Return Requested
- Returned
- Refunded

==================================================
12. ORDER TRACKING

Create a professional order tracking page.

Display:

- Order ID.
- Product.
- Delivery address.
- Expected delivery date.
- Current order status.
- Order timeline.
- Shipment information.

Users should be able to track their orders from their account.

==================================================
13. CUSTOMER ACCOUNT DASHBOARD

Create a complete customer dashboard.

Sections:

- My Profile
- My Orders
- Track Orders
- My Wishlist
- My Cart
- Saved Addresses
- My Reviews
- Notifications
- Coupons
- Help & Support
- Logout

==================================================
14. SELLER DASHBOARD

Create a separate seller registration and dashboard system.

Seller registration:

- Full name.
- Business name.
- Email.
- Phone.
- Business address.
- PAN details where required.
- GST information where applicable.
- Bank details through secure processes.
- Verification documents.

Seller dashboard:

- Overview
- Add Product
- Manage Products
- Edit Product
- Delete Product
- Product Inventory
- Manage Orders
- Sales Reports
- Earnings
- Returns
- Customer Reviews
- Seller Profile

Sellers must only access their own authorized products and orders.

Seller product publishing must follow admin approval rules.

==================================================
15. ADMIN DASHBOARD

Create a powerful administrator dashboard.

Dashboard overview:

- Total users.
- Total sellers.
- Total products.
- Total orders.
- Total revenue.
- Pending orders.
- Pending seller approvals.

Admin features:

- Manage Users.
- Manage Sellers.
- Approve/Reject Sellers.
- Manage Products.
- Approve/Reject Products.
- Manage Categories.
- Manage Orders.
- Manage Payments.
- Manage Refunds.
- Manage Coupons.
- Manage Banners.
- Manage Homepage Sections.
- Manage Reviews.
- Manage Notifications.
- Manage Customer Support.

Only authorized administrators can access admin features.

Admin roles must be verified securely through database policies or trusted backend functions, never through a frontend-only role check.

==================================================
16. COUPON AND OFFER SYSTEM

Implement:

- Percentage discount coupons.
- Fixed discount coupons.
- Minimum cart value.
- Maximum discount.
- Start date.
- Expiry date.
- Usage limits.
- Per-user usage limits.
- First-order coupons.
- Active/inactive coupon status.

Validate all coupons on the server before accepting an order.

==================================================
17. PRODUCT REVIEWS AND RATINGS

Features:

- Star ratings.
- Written reviews.
- Review images.
- Verified purchase indicator.
- Review moderation.
- Helpful votes.

Only eligible customers should be able to submit verified-purchase reviews.

==================================================
18. CUSTOMER SUPPORT

Create:

- Help Center.
- FAQ.
- Contact Us.
- Support tickets.
- Order-related complaints.
- Return and refund requests.

==================================================
19. DATABASE ARCHITECTURE – SUPABASE

Design a proper relational PostgreSQL schema.

Required tables:

1. profiles
2. user_roles
3. sellers
4. seller_documents
5. categories
6. brands
7. products
8. product_images
9. product_variants
10. product_inventory
11. carts
12. cart_items
13. wishlists
14. wishlist_items
15. addresses
16. orders
17. order_items
18. payments
19. coupons
20. coupon_usage
21. reviews
22. review_images
23. notifications
24. banners
25. support_tickets
26. return_requests
27. shipments
28. product_questions
29. product_answers
30. audit_logs

Database requirements:

- UUID primary keys.
- Foreign key relationships.
- Appropriate indexes.
- Created and updated timestamps.
- Unique constraints where needed.
- Proper numeric price fields.
- Stock validation.
- Secure RLS policies.
- Role-based access control.

Create SQL migrations in logical order.

Create appropriate Supabase Storage buckets:

- product-images
- product-banners
- profile-images
- seller-documents

Configure secure access policies for every bucket.

==================================================
20. SECURITY AND DATA VALIDATION

Implement:

- Supabase RLS.
- Server-side price validation.
- Stock validation.
- Secure checkout.
- Secure payment verification.
- Razorpay webhook verification.
- Protection against unauthorized admin access.
- Input validation.
- Error handling.
- Rate limiting where appropriate.
- Safe image uploads.
- Prevention of duplicate payment processing.
- Protection against order manipulation.

Never trust frontend-supplied product prices, discounts, order totals, seller IDs, or payment status.

==================================================
21. GITHUB PAGES DEPLOYMENT

The frontend must be deployable using GitHub Pages.

Requirements:

- Correct repository structure.
- index.html as the homepage.
- Relative asset paths.
- Mobile-friendly layout.
- No dependency on a local development server for basic browsing.
- Handle GitHub Pages refresh and routing correctly.
- Configure a suitable fallback or hash-based routing strategy.
- Provide exact GitHub deployment instructions.

Use Supabase as the hosted backend because GitHub Pages does not run server-side application code.

==================================================
22. CODE ORGANIZATION

Keep code clean, maintainable and modular.

Suggested structure:

MegaMart/
index.html
assets/
css/
style.css
responsive.css
js/
app.js
supabase.js
auth.js
products.js
search.js
cart.js
wishlist.js
checkout.js
orders.js
seller.js
admin.js
images/
logo/
banners/
icons/
pages/
login.html
signup.html
products.html
product-details.html
cart.html
checkout.html
orders.html
profile.html
seller-dashboard.html
admin-dashboard.html
supabase/
migrations/
functions/

You may improve this architecture if necessary, but maintain clear separation of responsibilities.

==================================================
23. PERFORMANCE AND RESPONSIVENESS

Requirements:

- Fast page loading.
- Optimized images.
- Lazy loading.
- Responsive product grids.
- Efficient database queries.
- Pagination.
- Loading indicators.
- Empty states.
- Error states.
- Accessible forms.
- Keyboard navigation.
- Good contrast.
- SEO metadata.
- Semantic HTML.

==================================================
24. DEVELOPMENT AND DELIVERY RULES

Follow these rules strictly:

1. Do not create a non-functional visual-only demo.
2. Every button must have a real working action.
3. Every navigation link must lead to the correct page.
4. All product data must come from Supabase.
5. Authentication must work.
6. Cart and wishlist must work.
7. Orders must be saved in Supabase.
8. Admin and seller permissions must be secure.
9. Payment integration must be real and securely verified.
10. Do not use fake success messages.
11. Do not break existing working functionality when updating code.
12. Do not leave important functions as TODO placeholders.
13. Do not invent API credentials.
14. Clearly identify configuration values that the owner must provide.
15. Test the complete customer shopping flow.

IMPORTANT OWNER WORKFLOW:

The owner primarily works from an Android phone and edits files using GitHub.

Therefore:

- Give exact file names.
- Give complete replacement code for each requested file.
- Explain exactly where each code block belongs.
- Provide complete SQL scripts ready to paste into Supabase SQL Editor.
- Avoid unnecessary manual terminal commands.
- Do not make unrelated changes.
- Never omit code required by another feature.

==================================================
25. FINAL PROJECT DELIVERY

Deliver the project in a structured sequence:

PHASE 1: Finalize UI/UX design and page layouts.

PHASE 2: Create complete frontend files.

PHASE 3: Create Supabase database schema and SQL migrations.

PHASE 4: Configure authentication, RLS and storage.

PHASE 5: Implement customer shopping functionality.

PHASE 6: Implement seller dashboard.

PHASE 7: Implement admin dashboard.

PHASE 8: Implement secure payment and order management.

PHASE 9: Test all user flows and fix bugs.

PHASE 10: Deploy on GitHub Pages.

Before declaring the project complete, verify:

- Registration and login.
- Product browsing and search.
- Product details.
- Cart.
- Wishlist.
- Checkout.
- Payment verification.
- Order tracking.
- Seller product management.
- Admin controls.
- Mobile responsiveness.
- Database security.

FINAL GOAL:

Build MegaMart as a complete, original, professional Indian e-commerce marketplace with a premium shopping experience, a fully functional Supabase backend, secure customer/seller/admin systems, and GitHub Pages deployment.

Do not sacrifice functionality for appearance. Both design quality and working features are equally important.
