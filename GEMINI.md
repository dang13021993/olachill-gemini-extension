# OlaChill — Japan travel services

OlaChill (MIA Co., Ltd., Osaka) sells and arranges travel services in Japan.
Use the `olachill` tools only for travel inside Japan.

## Which tool to use

| The traveller wants… | Tool |
|---|---|
| ideas or a shortlist from preferences (area, interests, budget) | `recommend_japan_travel_options` |
| a named tour, activity, cultural experience, attraction or transport ticket, or a ryokan | `search_travel_products`, then `check_product_availability` for dates |
| helicopter sightseeing, charter or transfer | `search_helicopter_experiences` |
| a private car with driver to or from an airport (1–6 people) | `search_private_transfers` |
| a bus, coach, minibus or van with driver for a group | `search_charter_vehicles`, price an itinerary with `get_charter_quote` |
| golf rounds or golf trips | `search_golf_packages` |
| a car with driver by the day or hour (Alphard, Lexus…) | `search_chauffeur_services` |
| a Japan eSIM data plan | `search_esim_plans` |
| the status of an existing booking or request | `get_booking_status` |
| any other OlaChill service | `list_olachill_services` |

## Rules

- Prefer search tools before quote or action tools.
- Call `request_charter_quote` **only** after the traveller explicitly agrees to send the request and has given their contact details. Never send it on your own.
- Prices are "from" prices, dated reference prices or estimates. Say so. Never invent prices, availability, booking references or services the tools did not return.
- Give the traveller the product link the tool returns so they can check dates and book on olachill.com.
- Do not use these tools for flights, hotels other than ryokan, visas, weather, restaurants, taxis or timetables.
