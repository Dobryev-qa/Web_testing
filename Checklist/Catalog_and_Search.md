# Checklist – Catalog and Search
> Module: Catalog and Search  
> Application: OpenCart Demo Web Shop

---

## Catalog

| ID | Check Item | Expected Result | Priority | Status | Remarks |
|----|-----------|-----------------|----------|--------|---------|
| CAT-01 | Navigate to any product category | Selected category page opens with correct list of products | High | Passed | |
| CAT-02 | Click each category in sidebar | Correct category opens with relevant items | High | Failed | Incorrect items displayed in Desktop category. Bug #2 |
| CAT-03 | Click category dropdown (Desktop, Laptops, Components, MP3 Players) | Dropdown opens; category list matches navigation menu | Medium | Passed | |
| CAT-04 | Click each dropdown category link | Correct product list opens | High | Passed | |
| CAT-05 | Click product category | Category description matches selected category | Medium | Passed | |
| CAT-06 | Sort By dropdown | Dropdown opens with options (Default, Name, Price, Rating, Model); selecting option updates product order | High | Passed | |
| CAT-07 | Display dropdown (items per page) | Changing number of items updates product list correctly | Medium | Passed | |
| CAT-08 | Pagination links | Clicking next/previous navigates between pages correctly | High | Passed | |

---

## Product Card

| ID | Check Item | Expected Result | Priority | Status | Remarks |
|----|-----------|-----------------|----------|--------|---------|
| PROD-01 | Verify product image | Image displays correctly; no broken images | High | Passed | |
| PROD-02 | Verify product name link | Product name is displayed correctly; clicking opens product details page | High | Passed | |
| PROD-03 | Verify product price | Price is displayed correctly according to selected currency | High | Passed | |
| PROD-04 | Verify "Add to Cart" button | Product is added to cart; confirmation message is displayed | High | Passed | |
| PROD-05 | Verify "Add to Wish List" button | Logged-in user: product added with confirmation; not logged-in user: login prompt displayed | High | Passed | |
| PROD-06 | Verify "Compare this product" button | Product is added to comparison list; confirmation message is displayed | Medium | Passed | |
| PROD-07 | Verify hover behavior | Product card highlights on hover; action buttons are visible | Low | Passed | |

---

## Search

| ID | Check Item | Expected Result | Priority | Status | Remarks |
|----|-----------|-----------------|----------|--------|---------|
| SRCH-01 | Click Search button with empty field | Redirects to Search page; message "There is no product that matches the search criteria" is displayed | Medium | Passed | |
| SRCH-02 | Search using full product name | Search Results page opens with correct matching products | High | Passed | |
| SRCH-03 | Search using part of product name | Search Results page opens with matching products | High | Passed | |
| SRCH-04 | Press Enter to search | Same result as clicking Search button | High | Passed | |
| SRCH-05 | Search with selected category | Correct product is displayed if available; message shown if not | High | Passed | |
| SRCH-06 | Enable product description checkbox | Search includes product descriptions | Medium | Passed | |
| SRCH-07 | Enable subcategories checkbox | Search includes products from subcategories | Medium | Passed | |
