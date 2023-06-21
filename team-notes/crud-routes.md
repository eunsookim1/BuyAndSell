1. **My Listings:**
   - **Read:** Retrieve a list of items the user has listed for sale.
   - **Update:** Edit the sale status of an item.
   - **Delete:** Remove an item from the site.

**Routes:**
- **GET /my-listings:** Retrieve the user's listed items.
- **PATCH /my-listings/{item_id}:** Update the sale status of a specific item.
- **DELETE /my-listings/{item_id}:** Delete a specific item from the user's listings.

2. **My Favourites:**
   - **Read:** Retrieve a list of items the user has favorited.
   - **Delete:** Remove an item from the user's favorites.

**Routes:**
- **GET /my-favourites:** Retrieve the user's favorited items.
- **DELETE /my-favourites/{item_id}:** Delete a specific item from the user's favorites.

3. **New Listing (for admins only):**
   - **Create:** Add a new item listing for sale.

**Routes:**
- **POST /new-listing:** Create a new item listing.
