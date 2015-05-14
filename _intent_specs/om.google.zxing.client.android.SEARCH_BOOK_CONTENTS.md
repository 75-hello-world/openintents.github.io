---
title: Search book contents
action: om.google.zxing.client.android.SEARCH_BOOK_CONTENTS
extras:
  -
    name: ISBN
    type: String
    description: The book to search, identified by ISBN number.
  -
    name: QUERY
    type: String
    description: An optional field which is the text to search for.
---
Use Google Book Search to search the contents of the book provided.

Intent specific extras:
ISBN: The book to search, identified by ISBN number.
QUERY: An optional field which is the text to search for.
