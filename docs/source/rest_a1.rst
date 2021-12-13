REST /a1
========

These endpoints are suitable for getting the data AS IS via "/?__a=1"

.. _examples:

Examples
------------

Getting user data:

.. code-block:: console

   curl -XGET https://api.lamadava.com/a1/user?username=instagram
   {
      "seo_category_infos": [],
      "logging_page_id": "profilePage_25025320",
      "show_suggested_profiles": true,
      "show_follow_dialog": false,
      "graphql": {
         "user": {
            "biography": "#YoursToMake",
            "blocked_by_viewer": false,
            "restricted_by_viewer": false,
            "country_block": false,
            "external_url": "http://help.instagram.com/",
            "external_url_linkshimmed": "https://l.instagram.com/?u=http%3A%2F%2Fhelp.instagram.com%2F&e=ATMXc26fv2A6EcmfucWSZRxxIMaTiKiYDliv8gnMwkF9qY5Fpy2LNT9MQrwuCxnmPkrt_muIATkcetkfPI3xy6s&s=1",
            "edge_followed_by": {"count": 449062512},
            "fbid": "17841400039600391",
            "followed_by_viewer": false,
            "edge_follow": {"count": 90},
            "follows_viewer": false,
            "full_name": "Instagram",
            "has_ar_effects": false,
            "has_clips": true,
            "has_guides": true,
            "has_channel": false,
            "has_blocked_viewer": false,
            "highlight_reel_count": 16,
            "has_requested_viewer": false,
            "hide_like_and_view_counts": false,
            "id": "25025320",
            "is_business_account": false,
            "is_professional_account": true,
            "is_embeds_disabled": false,
            "is_joined_recently": false,
            "business_address_json": null,
            "business_contact_method": null,
            "business_email": null,
            "business_phone_number": null,
            "business_category_name": null,
            "overall_category_name": null,
            "category_enum": null,
            "category_name": "Digital creator",
            "is_private": false,
            "is_verified": true,
            "edge_mutual_followed_by": {
               "count": 0,
               "edges": []
            },
            "profile_pic_url": "https://scontent-frx5-2.cdninstagram.com/v/t51.2885-19/s150x150/203019087_3969530746500786_7930596639916235962_n.jpg?_nc_ht=scontent-frx5-2.cdninstagram.com&_nc_cat=1&_nc_ohc=uAhnSbGAIkoAX-0x-QT&edm=ABfd0MgBAAAA&ccb=7-4&oh=00_AT-G1ri7Vz1MxR8z7KzzXnhfwygqEi00kcjpObv1ZPrR2g&oe=61BF67A6&_nc_sid=7bff83",
            "profile_pic_url_hd": "https://scontent-frx5-2.cdninstagram.com/v/t51.2885-19/s320x320/203019087_3969530746500786_7930596639916235962_n.jpg?_nc_ht=scontent-frx5-2.cdninstagram.com&_nc_cat=1&_nc_ohc=uAhnSbGAIkoAX-0x-QT&edm=ABfd0MgBAAAA&ccb=7-4&oh=00_AT_eHjW2an6D-DKPZODiAb6QLW-ZDzClVorqGL4fqH4Z9Q&oe=61BF7C73&_nc_sid=7bff83",
            "requested_by_viewer": false,
            "should_show_category": false,
            "should_show_public_contacts": false,
            "username": "instagram",
            "connected_fb_page": null,
            "pronouns": [],
            "edge_felix_video_timeline": {},
            "edge_owner_to_timeline_media": {},
            "edge_saved_media": {},
            "edge_media_collections": {}
         }
      },
      "toast_content_on_load": null,
      "show_view_shop": false,
      "profile_pic_edit_sync_props": {},
      "always_show_message_button_to_pro_account": false
   }


Getting post data:

.. code-block:: console

   curl -XGET https://api.lamadava.com/a1/media?code=CVx5hYTv4cT
   {
   "graphql": {
      "shortcode_media": {
         "__typename": "GraphImage",
         "id": "2698190634266625811",
         "shortcode": "CVx5hYTv4cT",
         "dimensions": {
            "height": 1350,
            "width": 1080
         },
         "gating_info": null,
         "fact_check_overall_rating": null,
         "fact_check_information": null,
         "sensitivity_friction_info": null,
         "sharing_friction_info": {
            "should_have_sharing_friction": false,
            "bloks_app_url": null
         },
         "media_overlay_info": null,
         "media_preview": "ACEqgBUc5/UmpTnAZvut09Of84FQIi5wcE9uOP8AE08mbbxgtnHIyAOe38qlsaRZOcA59fcUhyg9BVS0eQMySc5Gc+/T+mKLx9uUJ6/yHb86ndlbE3ne9FZ2IvU/kf8AGinYVy8i4kBHTkH2GOv1BFWLeAbixJLevbnt9PepI1RFYtgHjH/1qyGvJEkynQcY9fr71Osr2Kva3qbSWoxuP3z0Pp7VSubR3cnuR/nH1p8uqADKqQSOckcfh3/SqkN7MOCxPOcNz+HtSSkv+CDknoxvkf8ATNvzoq/9t9j+lFXr2/EnTv8AgRNcCUbQMk8CqYiKuQ3D9D9P8altP9ePr/jRJy7E9dy/zFVsIDbmZiVxx6+tVsOj4bhu+f6VrWg+Vv8AfNQakB8p781Cl71iraXIN9FMorYzP//Z",
         "display_url": "https://scontent-vie1-1.cdninstagram.com/v/t51.2885-15/252060074_962415954487436_2310073533762007038_n.jpg?stp=dst-jpg_e35_p1080x1080&cb=9ad74b5e-7e291d1f&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_ohc=x94txr9cqjUAX_NwfiE&tn=W2W4LclZW91_0BHq&edm=AABBvjUBAAAA&ccb=7-4&oh=00_AT_tV5QpNBqcevlooXLc4SLJWGMYAItHkkz9l8re1Ze46w&oe=61BE80EF&_nc_sid=83d603",
         "display_resources": [
            {
               "src": "https://scontent-vie1-1.cdninstagram.com/v/t51.2885-15/252060074_962415954487436_2310073533762007038_n.jpg?stp=dst-jpg_e35_p640x640_sh0.08&cb=9ad74b5e-7e291d1f&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_ohc=x94txr9cqjUAX_NwfiE&tn=W2W4LclZW91_0BHq&edm=AABBvjUBAAAA&ccb=7-4&oh=00_AT9bokaTNhbCv729v9MZmV4ji2yVaeGXmE94lnQWYIn5CA&oe=61BE80EF&_nc_sid=83d603",
               "config_width": 640,
               "config_height": 800
            },
            {
               "src": "https://scontent-vie1-1.cdninstagram.com/v/t51.2885-15/252060074_962415954487436_2310073533762007038_n.jpg?stp=dst-jpg_e35_p750x750_sh0.08&cb=9ad74b5e-7e291d1f&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_ohc=x94txr9cqjUAX_NwfiE&tn=W2W4LclZW91_0BHq&edm=AABBvjUBAAAA&ccb=7-4&oh=00_AT_kDEEqk_zzaMikj8xzjOvHAGtKdf_NBomFk1-M4o4e6Q&oe=61BE80EF&_nc_sid=83d603",
               "config_width": 750,
               "config_height": 937
            },
            {
               "src": "https://scontent-vie1-1.cdninstagram.com/v/t51.2885-15/252060074_962415954487436_2310073533762007038_n.jpg?stp=dst-jpg_e35_p1080x1080&cb=9ad74b5e-7e291d1f&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_ohc=x94txr9cqjUAX_NwfiE&tn=W2W4LclZW91_0BHq&edm=AABBvjUBAAAA&ccb=7-4&oh=00_AT_tV5QpNBqcevlooXLc4SLJWGMYAItHkkz9l8re1Ze46w&oe=61BE80EF&_nc_sid=83d603",
               "config_width": 1080,
               "config_height": 1350
            }
         ],
         "accessibility_caption": "A man wearing a yellow T-shirt and headphones sits on a rock by the water while holding up both hands, giving the peace sign.",
         "is_video": false,
         "tracking_token": "eyJ2ZXJzaW9uIjo1LCJwYXlsb2FkIjp7ImlzX2FuYWx5dGljc190cmFja2VkIjp0cnVlLCJ1dWlkIjoiZWM2MjE3Zjg3YmRjNDY3ZDg5MWYxMThkMWU4ZDlhOWUyNjk4MTkwNjM0MjY2NjI1ODExIiwic2VydmVyX3Rva2VuIjoiMTYzOTQyODk5ODkzNnwyNjk4MTkwNjM0MjY2NjI1ODExfDUwNzI3NzczNzU1fDEzNDQ1YWI0ZTJhZGQyOTA4Y2Q2MmFlYzgxN2NjYWMyYmY4ODRkZDkyMzhjMjQzMzkxNTVlYzk1YjI3ZjdkYjkifSwic2lnbmF0dXJlIjoiIn0=",
         "upcoming_event": null,
         "edge_media_to_tagged_user": {
            "edges": [{
               "node": {
                  "user": {
                     "full_name": "ben de almeida",
                     "followed_by_viewer": false,
                     "id": "104978309",
                     "is_verified": true,
                     "profile_pic_url": "https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/172449868_2874119579519069_9220724605010584396_n.jpg?stp=dst-jpg_s150x150&cb=9ad74b5e-7e291d1f&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_ohc=MSaQ21BRerEAX8x3Cg4&edm=AABBvjUBAAAA&ccb=7-4&oh=00_AT-g9ugCS0f1WisdPUEbEovhG855BscEvo1fY4bt54Twpw&oe=61BEC920&_nc_sid=83d603",
                     "username": "benoftheweek"
                  },
                  "x": 0.4888888628,
                  "y": 0.6376068115
               }
            }]
         },
         "edge_media_to_caption": {
            "edges": [
               {
                  "node": {
                     "text": "“Sometimes my mind feels like it has a bunch of monkeys jumping around, rearranging my brain cells,” says self-proclaimed “internet joke man” Ben De Almeida (@benoftheweek), who channels that same energy into his videos. “I love taking small ideas to the max and seeing what insane situations I get myself into. It’s pretty much the only thing that gets me out of the house.”⁣\n⁣\n“I try to create scenarios that almost feel like they could really be happening, but are just a touch too absurd to be real. I want my videos to feel like a friend telling you a made-up story about their day, and you know it’s 100% cap [fake] but it’s still entertaining.⁣\n⁣\nThe world can be so dark. Humor has been the only thing that can help me sometimes. Knowing that my videos can do that for even one person is insane.”⁣\n⁣\nPhoto by @benoftheweek"
                  }
               }
            ]
         },
         "can_see_insights_as_brand": false,
         "caption_is_edited": false,
         "has_ranked_comments": true,
         "like_and_view_counts_disabled": false,
         "edge_media_to_parent_comment": {},
         "edge_media_to_hoisted_comment": {},
         "edge_media_preview_comment": {},
         "comments_disabled": false,
         "commenting_disabled_for_viewer": false,
         "taken_at_timestamp": 1635869410,
         "edge_media_preview_like": {
            "count": 611209,
            "edges": []
         },
         "edge_media_to_sponsor_user": {
            "edges": []
         },
         "is_affiliate": false,
         "is_paid_partnership": false,
         "location": null,
         "viewer_has_liked": false,
         "viewer_has_saved": false,
         "viewer_has_saved_to_collection": false,
         "viewer_in_photo_of_you": false,
         "viewer_can_reshare": true,
         "owner": {
            "id": "25025320",
            "is_verified": true,
            "profile_pic_url": "https://scontent-vie1-1.cdninstagram.com/v/t51.2885-19/203019087_3969530746500786_7930596639916235962_n.jpg?stp=dst-jpg_s150x150&cb=9ad74b5e-7e291d1f&_nc_ht=scontent-vie1-1.cdninstagram.com&_nc_cat=1&_nc_ohc=uAhnSbGAIkoAX_56JSm&edm=AABBvjUBAAAA&ccb=7-4&oh=00_AT-_0niBTLuJ2Gr6pkER1RaA348XTCvPXhe5bguhUBQJBw&oe=61BE6EC2&_nc_sid=83d603",
            "username": "instagram",
            "blocked_by_viewer": false,
            "restricted_by_viewer": false,
            "followed_by_viewer": false,
            "full_name": "Instagram",
            "has_blocked_viewer": false,
            "is_embeds_disabled": false,
            "is_private": false,
            "is_unpublished": false,
            "requested_by_viewer": false,
            "pass_tiering_recommendation": true,
            "edge_owner_to_timeline_media": {
            "count": 7007
         },
         "edge_followed_by": {
            "count": 449065396
         }
         },
         "is_ad": false,
         "edge_web_media_to_related_media": {
            "edges": []
         },
         "coauthor_producers": [],
         "edge_related_profiles": {
            "edges": []
         }
         }
      }
   }
