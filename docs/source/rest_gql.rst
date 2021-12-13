REST /gql
===========

Getting data from the GraphQL API

.. _examples:

Examples
------------

Getting comments:

.. code-block:: console

   curl -XGET https://api.lamadava.com/gql/comments?media_id=2698190634266625811&amount=1
   [
      {
         "id": "17871375683538333",
         "text": "😍😍😍",
         "created_at": 1635869420,
         "did_report_as_spam": false,
         "owner": {
            "id": "33259029032",
            "is_verified": false,
            "profile_pic_url": "https://scontent-hel3-1.cdninstagram.com/v/t51.2885-19/s150x150/265325054_600493627943207_8134759777904168805_n.jpg?_nc_ht=scontent-hel3-1.cdninstagram.com&_nc_cat=111&_nc_ohc=HbUBWAAxmFMAX9c3rXB&edm=AP_V10EBAAAA&ccb=7-4&oh=00_AT9u8eAtswXDA3AITFD7NkFsUXz2ZBq9hYwd5DQimVlifA&oe=61BE9FFF&_nc_sid=4f375e",
            "username": "rocky_.rajput._143"
         },
         "viewer_has_liked": false,
         "edge_liked_by": {
            "count": 258
         },
         "edge_threaded_comments": {
            "count": 16,
            "page_info": {
            "has_next_page": false,
            "end_cursor": null
            },
            "edges": [
               {
                  "node": {
                     "id": "17913343571118278",
                     "text": "@rocky_.rajput._143 😍😍😍😍😍",
                     "created_at": 1635869520,
                     "did_report_as_spam": false,
                     "owner": {
                        "id": "29548602880",
                        "is_verified": false,
                        "profile_pic_url": "https://scontent-hel3-1.cdninstagram.com/v/t51.2885-19/s150x150/262499992_576352550101706_6086371710024400509_n.jpg?_nc_ht=scontent-hel3-1.cdninstagram.com&_nc_cat=102&_nc_ohc=z1GbWvmZY-QAX_QLIqK&edm=AP_V10EBAAAA&ccb=7-4&oh=00_AT8ujqVq9l2zypWLrVT0o6UEdmRNA4o9QKBcwKk2WVvMAA&oe=61BDE643&_nc_sid=4f375e",
                        "username": "___pata____nahi____"
                     },
                     "viewer_has_liked": false,
                     "edge_liked_by": {
                        "count": 3
                     }
                  }
               }
            }
         ]
         }
      }
   ]

