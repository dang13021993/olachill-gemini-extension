# OlaChill for Gemini CLI

Find and price Japan travel services from [OlaChill](https://olachill.com) directly in Gemini CLI:
tours and day trips, activities, attraction and transport tickets, ryokan, private airport
transfers, cars with driver, charter buses, helicopter flights, golf and Japan eSIM.

The extension connects Gemini CLI to OlaChill's public MCP server at `https://olachill.com/mcp`.
No API key is needed.

## Install

```bash
gemini extensions install https://github.com/dang13021993/olachill-gemini-extension
```

Then start Gemini CLI and check the connection:

```bash
gemini
/mcp
```

The `olachill` server should show as connected with 13 tools.

## Example prompts

- "Private transfer from Kansai Airport to Namba for 4 people"
- "Day tour to Mt Fuji from Tokyo next Saturday for 2 adults"
- "Helicopter night flight over Tokyo for a proposal"
- "Alphard with driver for a full day in Kyoto for 5 people"
- "Unlimited data eSIM for 10 days in Japan"
- "Coach for 40 people from Tokyo to Hakone and back, 2 days"

## Tools

| Tool | What it does |
|---|---|
| `recommend_japan_travel_options` | Shortlist of tours, activities, tickets or ryokan from preferences |
| `search_travel_products` | Search tours, activities, tickets and ryokan |
| `check_product_availability` | Dates and availability for a product |
| `search_helicopter_experiences` | Helicopter sightseeing, charter and transfer |
| `search_private_transfers` | Private airport transfers with driver |
| `search_charter_vehicles` | Buses, coaches, minibuses and vans with driver |
| `get_charter_quote` | Estimate for a charter itinerary |
| `request_charter_quote` | Send a quote request (only after the traveller agrees) |
| `search_chauffeur_services` | Cars with driver by the day or hour |
| `search_golf_packages` | Golf rounds and golf trips |
| `search_esim_plans` | Japan eSIM data plans |
| `get_booking_status` | Status of an existing booking or request |
| `list_olachill_services` | Overview of OlaChill services |

Prices are "from" prices or estimates; final price and availability are confirmed on olachill.com.

## Uninstall

```bash
gemini extensions uninstall olachill
```

## Contact

partners@olachill.com · https://olachill.com
