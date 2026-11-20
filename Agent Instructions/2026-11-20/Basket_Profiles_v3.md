# Basket Profiles

Knowledge source for AVA's basket builder. Use it for every product recommendation, including requests that name a need such as dental, joints, digestion, skin and coat, weight, urinary, hairballs or anxiety. Built on November 10, 2026 from the full Pet Valu product feed (7,903 active products). Every basket item below was checked against real products in the catalogue, using category, pet type, life stage, pet size, breed, health benefit, product type, flavour, title and description together.

This file tells AVA **which product categories and labels to use** for a pet. It is not a price list or a stock list, and it lists no products. AVA finds the products for each basket item with its own website search, using the item's Search line.

## 1. How to use this file

- **Every product recommendation is a basket.** Any request to recommend, suggest, find or compare products for a pet gets a basket, never a plain product list. Start the answer with "Profile: [profile name]", using the profile heading(s) below.
- **A health need in a product request still gets a basket.** "Dog food for dental issues", "something for joint problems" or "food for a sensitive stomach" are product requests: use the matching need profile in section 7 or 9, build the basket, then add one line that the DPL should check with their vet for any pain or diagnosed condition.
- **Match in this order:** breed profile (if a breed is named and listed in section 10) → need or situation profile → life stage and size profile → fallback profile for the pet type.
- **Compose, don't pick just one.** For dogs and cats, start with the base profile for the pet's age (and size, for dogs), then apply every modifier that matches the answers given: activity or lifestyle, goal, foods to avoid, and needs. A modifier swaps the food filter or adds items; it never removes the category the ACE asked about.
- **Order of the basket:** the category the ACE asked about first, then the Treat of the Month (from AVA's instructions, for dogs and cats), then the profile's items in the order listed. Show 5 categories, fewer only if the profile has fewer. Modifier items go right after the food. Every category must show products.
- **Products for each item:** run a separate website search for every basket item, all at once, using its "Search" line plus the pet's details (life stage, size, breed, foods to avoid). Show 3 products for the category the ACE asked about and 2 for each other item, each linked to its petvalu.ca/product/ page with the rating shown there. Don't repeat a product across categories. If a search finds no matching product page, replace that item with the next one in the profile.
- **Search with the exact category names** shown under "Category" (for example `Dog > Food > Dry Food`). They are the names used on petvalu.ca. Then narrow with the "Look for" words.
- **Labels are often missing from our data.** A product with no life stage, size or health label is not excluded by that alone. Use the product page to confirm. Section 3 lists which labels are reliable.
- **"In catalogue" counts** show how many products match each filter, from strictest to loosest. If the strictest filter has few or no products, use the next one and say so (for example, "We don't carry a senior large-breed formula in this line, so here are senior foods for all sizes").
- **Foods to avoid:** shortlist with the rules in section 6, then tell the ACE to check the ingredient list on the product page or the bag. Never state that a product is free of an ingredient unless its page says so.
- **Health and weight:** choose products by their page labels only and make no health claims. Still build the basket, and add one line that the DPL should speak to their vet about a diagnosed condition, weight-loss targets or any symptom. Never recommend prescription diets.
- **Sales prompts:** each item has an "Ask the DPL" line. Ask about habits and needs, never symptoms. Skip the prompt for the category the ACE asked about.
- **No match at all:** use the fallback profile for the pet type (section 13). If the pet type or species is unknown, ask the one question the fallback gives before showing products.
- **Guardrails** under a profile apply only when the DPL describes the specific signs listed there. Otherwise, build the basket.
- **Only these skip the basket:** policy questions, general pet-care questions, and questions about what a symptom means or how to treat it. Emergencies (poisoning, breathing trouble, seizures, swallowed objects, a cat that cannot pee): tell the ACE the DPL should contact a vet immediately.

## 2. Catalogue map

These are the real category names and how many products sit in each, after reading every category path on each product (many products are listed under more than one pet or category).

**Dog** (4,890 products)

- Dog > Food > Broths & Food Toppers (81)
- Dog > Food > Dehydrated & Air Dried Food (41)
- Dog > Food > Dry Food (553)
- Dog > Food > Freeze Dried Food (97)
- Dog > Food > Gently Cooked Food (11)
- Dog > Food > Raw Food (78)
- Dog > Food > Wet Food (424)
- Dog > Supplies > Beds & Mats (86): Beds (66), Crate Mats & Pads (11), Floor Mats (9)
- Dog > Supplies > Bowls & Feeding (194): Bowls (68), Feeders & Waterers (15), Filters & Pumps (12), Food Mats (18), Food Storage Containers & Accessories (18), Slow Feeders (36), Water Bottles & Travel Bowls (30)
- Dog > Supplies > Carriers & Travel Accessories (91): Car Accessories (46), Carriers & Strollers (17), Travel Aids (20)
- Dog > Supplies > Clean Up & Potty Pads (57): Diapers & Potty Pads (9), Poop Bags & Scoopers (29), Stain & Odour Removers (15)
- Dog > Supplies > Clothing & Accessories (247): Bandanas & Accessories (44), Boots & Socks (33), Coats & Jackets (62), Costumes (24), Jerseys & Sports Teams (5), Life Jackets & Raincoats (40), Shirts & Dresses (12), Sweaters & Hoodies (27)
- Dog > Supplies > Collars, Leashes & Harnesses (614): Collars (156), Harnesses (108), ID Tags & Accessories (128), Leashes (202), Muzzles & Head Collars (6), Tie Outs (18)
- Dog > Supplies > Crates, Pens & Gates (51): Crate Mats & Accessories (9), Crates & Pens (11), Doors & Gates (14), Fence Systems (14)
- Dog > Supplies > Flea & Tick (49): Combs & Accessories (7), Repellents & Treatment Sprays (6), Spot Treatments (30)
- Dog > Supplies > Gifts (24)
- Dog > Supplies > Grooming (152): Brushes & Combs (32), Deodorizers & Wipes (31), Deshedding Solutions (17), Eye & Ear Care (5), Paw & Nail Care (12), Shampoos & Conditioners (51), Towels & Accessories (6)
- Dog > Supplies > Health & Wellness (242): Calming & Anxiety (23), Dental & Breath Care (34), Digestive Care (37), Eye & Ear Care (14), First Aid & Recovery (20), Hip & Joint Care (35), Skin & Coat Care (35), Urinary Care (8), Vitamins & Supplements (48)
- Dog > Supplies > Toys (753): Balls & Fetch Toys (76), Chew Toys (87), Interactive & Puzzle Toys (99), Plush Toys (313), Rope & Tug Toys (125), Tough & Durable Toys (269)
- Dog > Supplies > Training & Behaviour (99): Bark Control & Remote Training (14), Fence Systems (18), Potty Training Aids (22), Repellents & Deterrents (13), Training Collars & Leashes (27)
- Dog > Treats > Bakery & Biscuits (268)
- Dog > Treats > Bones & Chews (311)
- Dog > Treats > Dental Chews & Treats (91)
- Dog > Treats > Freeze Dried & Dehydrated Treats (117)
- Dog > Treats > Frozen Treats (40)
- Dog > Treats > Jerky Treats (28)
- Dog > Treats > Soft & Chewy Treats (184)
- Dog > Treats > Training Treats (168)

**Cat** (2,303 products)

- Cat > Food & Treats > Broths & Food Toppers (90)
- Cat > Food & Treats > Dry Food (216)
- Cat > Food & Treats > Freeze Dried, Dehydrated & Air Dried Food (38)
- Cat > Food & Treats > Raw Food (31)
- Cat > Food & Treats > Treats (170): Crunchy Treats (34), Freeze Dried & Dehydrated Treats (50), Frozen Treats (5), Soft & Chewy Treats (37)
- Cat > Food & Treats > Wet Food (602)
- Cat > Litter & Accessories > Litter (70)
- Cat > Litter & Accessories > Litter Boxes (32)
- Cat > Litter & Accessories > Litter Mats & Accessories (43)
- Cat > Litter & Accessories > Litter Waste Disposal (14)
- Cat > Supplies > Beds (28)
- Cat > Supplies > Bowls & Feeding (157): Bowls (56), Feeders & Waterers (28), Filters & Pumps (20), Food Storage Containers & Accessories (21), Placemats (11), Slow Feeders (20)
- Cat > Supplies > Carriers & Travel Accessories (47): Carriers & Strollers (19), Doors & Gates (8), Training & Behaviour (5), Travel Aids (12)
- Cat > Supplies > Cleaning & Repellents (23): Repellents & Training Aids (10), Stain & Odour Removers (13)
- Cat > Supplies > Collars, Leashes & Harnesses (174): Collars (40), ID Tags & Accessories (104), Leashes & Harnesses (29)
- Cat > Supplies > Flea & Tick (23)
- Cat > Supplies > Furniture & Scratchers (78): Scratchers & Posts (37), Trees & Condos (41)
- Cat > Supplies > Gifts (8)
- Cat > Supplies > Grooming (79): Deodorizers & Wipes (23), Grooming Tools (27), Shampoos & Conditioners (22), Towels & Accessories (6)
- Cat > Supplies > Health & Wellness (161): Calming & Anxiety (10), Dental & Breath Care (20), Eye & Ear Care (5), First Aid & Recovery (11), Hairball Control (7), Hip & Joint Care (21), Probiotics & Digestive Care (29), Skin & Coat Care (18), Urinary Care (10), Vitamins & Supplements (38)
- Cat > Supplies > Toys (300): Ball Toys (26), Catnip & Grass (33), Kickers (19), Lasers & Interactive Toys (69), Plush Toys (107), Teasers & Wands (38), Tunnels (10)

**Small Pet** (429 products)

- Small Pet > Food, Treats & Hay > Food (76)
- Small Pet > Food, Treats & Hay > Hay (29)
- Small Pet > Food, Treats & Hay > Treats (94)
- Small Pet > Supplies > Bedding & Litter (28)
- Small Pet > Supplies > Bowls & Water Bottles (22)
- Small Pet > Supplies > Cages, Habitats & Hutches (23)
- Small Pet > Supplies > Harnesses & Carriers (6)
- Small Pet > Supplies > Health & Grooming (55)
- Small Pet > Supplies > Hideouts, Toys & Accessories (94): Habitat Accessories (31), Hideouts (19), Toys (43)

**Bird** (240 products)

- Bird > Food & Treats > Canary & Finch (11)
- Bird > Food & Treats > Cockatiel & Conure (19)
- Bird > Food & Treats > Parakeet & Budgie (22)
- Bird > Food & Treats > Parrot & Macaw (25)
- Bird > Food & Treats > Treats (32)
- Bird > Food & Treats > Wild Bird (16)
- Bird > Supplies > Cages & Cage Accessories (44): Cage Accessories (5), Cages & Stands (11), Feeders & Waterers (28)
- Bird > Supplies > Health & Wellness (13)
- Bird > Supplies > Perches, Swings & Ladders (22)
- Bird > Supplies > Toys (52)

**Fish** (368 products)

- Fish > Food > Betta (28)
- Fish > Food > Bottom Feeders (25)
- Fish > Food > Cichlid (25)
- Fish > Food > Goldfish (33)
- Fish > Food > Koi & Pond Fish (9)
- Fish > Food > Tropical Fish (28)
- Fish > Supplies > Aquarium Decor & Accessories (117): Accessories (14), Gravel (33), Ornaments (35), Plants (38)
- Fish > Supplies > Aquariums, Kits & Tanks (22)
- Fish > Supplies > Cleaning & Maintenance (10)
- Fish > Supplies > Filters & Media (93): Filter Media (72), Filters (19)
- Fish > Supplies > Fish Care (4)
- Fish > Supplies > Heating & Lighting (14)
- Fish > Supplies > Water Care (42): Water Balance (12), Water Conditioners (24), Water Treatment (8)

**Reptile** (179 products)

- Reptile > Food > Bearded Dragon (24)
- Reptile > Food > Frog (20)
- Reptile > Food > Gecko (22)
- Reptile > Food > Hermit Crab (12)
- Reptile > Food > Turtle (25)
- Reptile > Supplies > Habitat Decor & Accessories (45): Accessories (28), Decor (17)
- Reptile > Supplies > Habitats & Kits (15)
- Reptile > Supplies > Health & Wellness (14)
- Reptile > Supplies > Heating & Lighting (50)
- Reptile > Supplies > Substrate & Bedding (19)

## 3. How to read our product data

Our product attributes are incomplete, so the same fact can sit in different places. Check them in this order: the attribute field, then the product title and sub-brand, then the description.

| What you need | Where it shows up | How reliable |
|---|---|---|
| Life stage (food) | Life Stage attribute; title words "Puppy", "Junior", "Growth", "Senior", "Mature", "7+", "Aging", "All Life Stages" | Reliable on food: 1,180 of 1,228 dog foods and 816 of 818 cat dry and wet foods carry one. |
| Life stage (treats, supplies) | Title or description only | Rare: 167 of 1,059 dog treats mention one. Do not exclude a treat or supply for lacking it. |
| Dog size (food) | Pet Size attribute; title words "Small Breed", "Large Breed", "Mini", "Maxi", "Giant", "Toy", "X-Small"; description | 104 small, 10 medium and 85 large-breed dry foods. The Pet Size attribute covers 189 of them; the title and description supply the rest. The other 352 dry foods have no size label and suit all sizes. |
| Dog size (collars, harnesses, clothing, toys, beds) | The size options on the product (X-Small to XX-Large) | Reliable. Match the size to the dog using the sizing chart on the page. |
| Breed | Breed attribute; breed name in the title (Royal Canin breed lines) | The attribute is filled on 29 products; the title adds 18 more. See section 10 for every breed we carry. |
| Health need | Health Benefit attribute; Product Type; category; title; description | The attribute is filled on 2,027 dog and cat products. Descriptions mention needs far more often, but a mention is weaker than a label. Prefer labelled products. |
| Grain-free, limited ingredient, chicken free | Product Type attribute | Grain-free and limited ingredient are reliable. "Chicken Free" is tagged on 570 products and is trustworthy when present, but many chicken-free products are not tagged. |
| Ingredients | Not in the product data. Only the Flavour attribute, title and description name ingredients. | The product page usually shows the full ingredient list. The flavour is the main protein, not the full recipe. See section 6. |
| Small pet, bird, fish and reptile species | Pet Type attribute; species in the title; food categories named by species | Food is species-specific and reliable. Supplies are usually tagged for many species at once. |
| Starter items | "Puppy Essentials" and "Kitten Essentials" flags | 534 puppy and 314 kitten products are flagged across food, toys, beds, bowls, collars and more. |

**Words our catalogue uses**

- Small dogs: Small Breed, Small & Toy, Toy, Mini, X-Small, Small Bites, Little Bites.
- Large dogs: Large Breed, Giant, Maxi.
- Puppies and kittens: Puppy, Junior, Growth, Kitten.
- Seniors: Senior, Mature, 7+, 11+, Aging.
- Sensitive stomach: Digestive Care, Sensitive Stomach, Digestive Health, Probiotics, Gentle.
- Food sensitivities: Food Sensitivities, Allergy, Limited Ingredient (LID), Single Protein, Novel Protein, Hydrolyzed.
- Weight: Weight Control, Weight Management, Healthy Weight, Light, Lite, Lean, Low Fat.
- Joints: Hip & Joint, Mobility, Glucosamine.  Skin: Skin & Coat, Sensitive Skin, Omega.
- Active dogs: Sport, Performance, Active, High Energy, High Protein.
- Cats: Indoor, Hairball, Urinary Care, Multi Cat (litter).

## 4. Dog base profiles (age and size)

Pick one base profile from the dog's age and size, then add modifiers from sections 5, 6 and 7. Size guide: small is under about 10 kg, medium about 10 to 25 kg, large over about 25 kg.


### DOG · Puppy · Small

**Use when:** new puppy, puppy under 1 year; small dog.
**Keywords:** dog, puppy, small breed, small dog

**Basket items, in order:**

1. **Puppy dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog puppy dry food
   - Look for: "Puppy", "Junior", "Growth" and "Small Breed", "Small & Toy", "Toy", "Mini", "X-Small", "Small Bites"
   - In catalogue: puppy + small breed label: 27 → puppy-specific with no size label (suits all sizes): 49 → any food that includes puppies, no size label: 160 → all life stages: 138
2. **Puppy wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog puppy wet food or topper
   - Look for: "Puppy", "Junior", "Growth" on wet food; toppers suit any age
   - In catalogue: puppy-specific wet food: 22 → any wet food that includes puppies: 149 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Training treats**
   - Category: Dog > Treats; Dog > Treats > Training Treats
   - Search: dog training treats
   - Look for: small, soft treats; "Puppy" or "Training" in the name
   - In catalogue: treats labelled for puppies: 109 → training treats: 168
   - Ask the DPL: "Has training started? Small soft treats make it easier."
4. **Teething and chew toys**
   - Category: Dog > Supplies > Toys; Dog > Supplies > Toys > Chew Toys
   - Search: dog teething and chew toys
   - Look for: "Puppy" or "Teething" in the name
   - In catalogue: toys with a teething feature or puppy in the name: 19 → chew toys: 87
   - Ask the DPL: "Is the puppy chewing everything yet?"
5. **Collar or harness, and leash (small sizes)**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar or harness, and leash
   - Look for: sizes XX-Small, X-Small, Small, X-Small/Small; check the sizing chart on the product page
   - In catalogue: harnesses offered in small sizes: 97 → collars offered in small sizes: 128 → leashes: 202
   - Ask the DPL: "Does the dog walk on a collar or a harness right now?"
6. **Crate and crate pad**
   - Category: Dog > Supplies > Crates, Pens & Gates > Crates & Pens; Dog > Supplies > Beds & Mats > Crate Mats & Pads; Dog > Supplies > Crates, Pens & Gates > Crate Mats & Accessories
   - Search: dog crate and crate pad
   - Look for: crate sized for the dog's adult size
   - In catalogue: crates and pens: 11 → crate mats and pads: 20
   - Ask the DPL: "Will the puppy sleep in a crate?"
7. **Potty training supplies**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Diapers & Potty Pads; Dog > Supplies > Training & Behaviour > Potty Training Aids; Dog > Supplies > Clean Up & Potty Pads > Stain & Odour Removers
   - Search: dog potty training supplies
   - Look for: training pads, potty bells, stain and odour remover
   - In catalogue: potty pads and training aids: 31 → stain and odour removers: 15
   - Ask the DPL: "How is house training going?"
8. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"
9. **Bowl or slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls; Dog > Supplies > Bowls & Feeding > Slow Feeders
   - Search: dog bowl or slow feeder
   - Look for: bowl sized for the dog; slow feeder for fast eaters
   - In catalogue: bowls: 68 → slow feeders: 36
   - Ask the DPL: "Does the puppy have its own bowls yet?"

### DOG · Puppy · Medium

**Use when:** new puppy, puppy under 1 year; medium dog.
**Keywords:** dog, puppy, medium breed, medium dog

**Basket items, in order:**

1. **Puppy dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog puppy dry food
   - Look for: "Puppy", "Junior", "Growth" and "Medium Breed" (rarely labelled; most medium dogs use foods with no size label)
   - In catalogue: puppy + medium breed label: 2 → puppy-specific with no size label (suits all sizes): 49 → any food that includes puppies, no size label: 160 → all life stages: 138
2. **Puppy wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog puppy wet food or topper
   - Look for: "Puppy", "Junior", "Growth" on wet food; toppers suit any age
   - In catalogue: puppy-specific wet food: 22 → any wet food that includes puppies: 149 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Training treats**
   - Category: Dog > Treats; Dog > Treats > Training Treats
   - Search: dog training treats
   - Look for: small, soft treats; "Puppy" or "Training" in the name
   - In catalogue: treats labelled for puppies: 109 → training treats: 168
   - Ask the DPL: "Has training started? Small soft treats make it easier."
4. **Teething and chew toys**
   - Category: Dog > Supplies > Toys; Dog > Supplies > Toys > Chew Toys
   - Search: dog teething and chew toys
   - Look for: "Puppy" or "Teething" in the name
   - In catalogue: toys with a teething feature or puppy in the name: 19 → chew toys: 87
   - Ask the DPL: "Is the puppy chewing everything yet?"
5. **Collar or harness, and leash (medium sizes)**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar or harness, and leash
   - Look for: sizes Medium, Small/Medium, Medium/Large; check the sizing chart on the product page
   - In catalogue: harnesses offered in medium sizes: 79 → collars offered in medium sizes: 97 → leashes: 202
   - Ask the DPL: "Does the dog walk on a collar or a harness right now?"
6. **Crate and crate pad**
   - Category: Dog > Supplies > Crates, Pens & Gates > Crates & Pens; Dog > Supplies > Beds & Mats > Crate Mats & Pads; Dog > Supplies > Crates, Pens & Gates > Crate Mats & Accessories
   - Search: dog crate and crate pad
   - Look for: crate sized for the dog's adult size
   - In catalogue: crates and pens: 11 → crate mats and pads: 20
   - Ask the DPL: "Will the puppy sleep in a crate?"
7. **Potty training supplies**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Diapers & Potty Pads; Dog > Supplies > Training & Behaviour > Potty Training Aids; Dog > Supplies > Clean Up & Potty Pads > Stain & Odour Removers
   - Search: dog potty training supplies
   - Look for: training pads, potty bells, stain and odour remover
   - In catalogue: potty pads and training aids: 31 → stain and odour removers: 15
   - Ask the DPL: "How is house training going?"
8. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"
9. **Bowl or slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls; Dog > Supplies > Bowls & Feeding > Slow Feeders
   - Search: dog bowl or slow feeder
   - Look for: bowl sized for the dog; slow feeder for fast eaters
   - In catalogue: bowls: 68 → slow feeders: 36
   - Ask the DPL: "Does the puppy have its own bowls yet?"

### DOG · Puppy · Large

**Use when:** new puppy, puppy under 1 year; large dog.
**Keywords:** dog, puppy, large breed, large dog

**Basket items, in order:**

1. **Puppy dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog puppy dry food
   - Look for: "Puppy", "Junior", "Growth" and "Large Breed", "Giant", "Maxi"
   - In catalogue: puppy + large breed label: 26 → puppy-specific with no size label (suits all sizes): 49 → any food that includes puppies, no size label: 160 → all life stages: 138
2. **Puppy wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog puppy wet food or topper
   - Look for: "Puppy", "Junior", "Growth" on wet food; toppers suit any age
   - In catalogue: puppy-specific wet food: 22 → any wet food that includes puppies: 149 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Training treats**
   - Category: Dog > Treats; Dog > Treats > Training Treats
   - Search: dog training treats
   - Look for: small, soft treats; "Puppy" or "Training" in the name
   - In catalogue: treats labelled for puppies: 109 → training treats: 168
   - Ask the DPL: "Has training started? Small soft treats make it easier."
4. **Teething and chew toys**
   - Category: Dog > Supplies > Toys; Dog > Supplies > Toys > Chew Toys
   - Search: dog teething and chew toys
   - Look for: "Puppy" or "Teething" in the name
   - In catalogue: toys with a teething feature or puppy in the name: 19 → chew toys: 87
   - Ask the DPL: "Is the puppy chewing everything yet?"
5. **Collar or harness, and leash (large sizes)**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar or harness, and leash
   - Look for: sizes Large, X-Large, XX-Large, Large/X-Large, XXX-Large; check the sizing chart on the product page
   - In catalogue: harnesses offered in large sizes: 90 → collars offered in large sizes: 101 → leashes: 202
   - Ask the DPL: "Does the dog walk on a collar or a harness right now?"
6. **Crate and crate pad**
   - Category: Dog > Supplies > Crates, Pens & Gates > Crates & Pens; Dog > Supplies > Beds & Mats > Crate Mats & Pads; Dog > Supplies > Crates, Pens & Gates > Crate Mats & Accessories
   - Search: dog crate and crate pad
   - Look for: crate sized for the dog's adult size
   - In catalogue: crates and pens: 11 → crate mats and pads: 20
   - Ask the DPL: "Will the puppy sleep in a crate?"
7. **Potty training supplies**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Diapers & Potty Pads; Dog > Supplies > Training & Behaviour > Potty Training Aids; Dog > Supplies > Clean Up & Potty Pads > Stain & Odour Removers
   - Search: dog potty training supplies
   - Look for: training pads, potty bells, stain and odour remover
   - In catalogue: potty pads and training aids: 31 → stain and odour removers: 15
   - Ask the DPL: "How is house training going?"
8. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"
9. **Bowl or slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls; Dog > Supplies > Bowls & Feeding > Slow Feeders
   - Search: dog bowl or slow feeder
   - Look for: bowl sized for the dog; slow feeder for fast eaters
   - In catalogue: bowls: 68 → slow feeders: 36
   - Ask the DPL: "Does the puppy have its own bowls yet?"

### DOG · Adult · Small

**Use when:** adult dog, about 1 to 7 years; small dog.
**Keywords:** dog, adult, small breed, small dog

**Basket items, in order:**

1. **Adult dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog adult dry food
   - Look for: "Adult" and "Small Breed", "Small & Toy", "Toy", "Mini", "X-Small", "Small Bites"
   - In catalogue: adult + small breed label: 88 → adult-specific with no size label (suits all sizes): 166 → any food that includes adult dogs, no size label: 283 → all life stages: 138
2. **Adult wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog adult wet food or topper
   - Look for: "Adult" on wet food; toppers suit any age
   - In catalogue: adult-specific wet food: 232 → any wet food that includes adult dogs: 361 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Everyday treats**
   - Category: Dog > Treats > Soft & Chewy Treats; Dog > Treats > Bakery & Biscuits; Dog > Treats > Training Treats
   - Search: dog everyday treats
   - Look for: soft and chewy, biscuits or training treats
   - In catalogue: soft and chewy treats: 184 → bakery and biscuits: 268 → training treats: 168
   - Ask the DPL: "What treats does the dog usually get?"
4. **Dental chews**
   - Category: Dog > Treats > Dental Chews & Treats
   - Search: dog dental chews
   - Look for: dental chew sized for the dog's weight
   - In catalogue: dental chews and treats: 91
   - Ask the DPL: "Does the dog get anything for teeth day to day?"
5. **Toys for small dogs**
   - Category: Dog > Supplies > Toys > Plush Toys; Dog > Supplies > Toys > Balls & Fetch Toys
   - Search: toys for small dogs
   - Look for: plush and small balls
   - In catalogue: plush toys: 313 → balls and fetch toys offered in small sizes: 15
   - Ask the DPL: "How does the dog like to play?"
6. **Bowl or slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Slow Feeders; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog bowl or slow feeder
   - Look for: slow feeder for fast eaters
   - In catalogue: slow feeders: 36 → bowls: 68
   - Ask the DPL: "Does the dog finish meals quickly?"
7. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"
8. **Collar or harness, and leash (small sizes)**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar or harness, and leash
   - Look for: sizes XX-Small, X-Small, Small, X-Small/Small; check the sizing chart on the product page
   - In catalogue: harnesses offered in small sizes: 97 → collars offered in small sizes: 128 → leashes: 202
   - Ask the DPL: "Does the dog walk on a collar or a harness right now?"

### DOG · Adult · Medium

**Use when:** adult dog, about 1 to 7 years; medium dog.
**Keywords:** dog, adult, medium breed, medium dog

**Basket items, in order:**

1. **Adult dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog adult dry food
   - Look for: "Adult" and "Medium Breed" (rarely labelled; most medium dogs use foods with no size label)
   - In catalogue: adult + medium breed label: 8 → adult-specific with no size label (suits all sizes): 166 → any food that includes adult dogs, no size label: 283 → all life stages: 138
2. **Adult wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog adult wet food or topper
   - Look for: "Adult" on wet food; toppers suit any age
   - In catalogue: adult-specific wet food: 232 → any wet food that includes adult dogs: 361 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Everyday treats**
   - Category: Dog > Treats > Soft & Chewy Treats; Dog > Treats > Bakery & Biscuits; Dog > Treats > Training Treats
   - Search: dog everyday treats
   - Look for: soft and chewy, biscuits or training treats
   - In catalogue: soft and chewy treats: 184 → bakery and biscuits: 268 → training treats: 168
   - Ask the DPL: "What treats does the dog usually get?"
4. **Dental chews**
   - Category: Dog > Treats > Dental Chews & Treats
   - Search: dog dental chews
   - Look for: dental chew sized for the dog's weight
   - In catalogue: dental chews and treats: 91
   - Ask the DPL: "Does the dog get anything for teeth day to day?"
5. **Fetch and tug toys**
   - Category: Dog > Supplies > Toys > Balls & Fetch Toys; Dog > Supplies > Toys > Rope & Tug Toys
   - Search: dog fetch and tug toys
   - Look for: balls, rope and tug toys
   - In catalogue: balls and fetch toys: 76 → rope and tug toys: 125
   - Ask the DPL: "How does the dog like to play: fetch, tug or chew?"
6. **Bowl or slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Slow Feeders; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog bowl or slow feeder
   - Look for: slow feeder for fast eaters
   - In catalogue: slow feeders: 36 → bowls: 68
   - Ask the DPL: "Does the dog finish meals quickly?"
7. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"
8. **Collar or harness, and leash (medium sizes)**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar or harness, and leash
   - Look for: sizes Medium, Small/Medium, Medium/Large; check the sizing chart on the product page
   - In catalogue: harnesses offered in medium sizes: 79 → collars offered in medium sizes: 97 → leashes: 202
   - Ask the DPL: "Does the dog walk on a collar or a harness right now?"

### DOG · Adult · Large

**Use when:** adult dog, about 1 to 7 years; large dog.
**Keywords:** dog, adult, large breed, large dog

**Basket items, in order:**

1. **Adult dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog adult dry food
   - Look for: "Adult" and "Large Breed", "Giant", "Maxi"
   - In catalogue: adult + large breed label: 60 → adult-specific with no size label (suits all sizes): 166 → any food that includes adult dogs, no size label: 283 → all life stages: 138
2. **Adult wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog adult wet food or topper
   - Look for: "Adult" on wet food; toppers suit any age
   - In catalogue: adult-specific wet food: 232 → any wet food that includes adult dogs: 361 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Everyday treats**
   - Category: Dog > Treats > Soft & Chewy Treats; Dog > Treats > Bakery & Biscuits; Dog > Treats > Training Treats
   - Search: dog everyday treats
   - Look for: soft and chewy, biscuits or training treats
   - In catalogue: soft and chewy treats: 184 → bakery and biscuits: 268 → training treats: 168
   - Ask the DPL: "What treats does the dog usually get?"
4. **Dental chews**
   - Category: Dog > Treats > Dental Chews & Treats
   - Search: dog dental chews
   - Look for: dental chew sized for the dog's weight
   - In catalogue: dental chews and treats: 91
   - Ask the DPL: "Does the dog get anything for teeth day to day?"
5. **Tough toys for large dogs**
   - Category: Dog > Supplies > Toys > Tough & Durable Toys
   - Search: tough toys for large dogs
   - Look for: "Tough & Durable"; repeat only the page's durability wording
   - In catalogue: tough and durable toys offered in large sizes: 74 → tough and durable toys: 269
   - Ask the DPL: "Is the dog a strong chewer?"
6. **Bowl or slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Slow Feeders; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog bowl or slow feeder
   - Look for: slow feeder for fast eaters
   - In catalogue: slow feeders: 36 → bowls: 68
   - Ask the DPL: "Does the dog finish meals quickly?"
7. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"
8. **Collar or harness, and leash (large sizes)**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar or harness, and leash
   - Look for: sizes Large, X-Large, XX-Large, Large/X-Large, XXX-Large; check the sizing chart on the product page
   - In catalogue: harnesses offered in large sizes: 90 → collars offered in large sizes: 101 → leashes: 202
   - Ask the DPL: "Does the dog walk on a collar or a harness right now?"

### DOG · Senior · Small

**Use when:** senior or older dog, about 7 years and up; small dog.
**Keywords:** dog, senior, small breed, small dog

**Basket items, in order:**

1. **Senior dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog senior dry food
   - Look for: "Senior", "Mature", "7+", "Aging" and "Small Breed", "Small & Toy", "Toy", "Mini", "X-Small", "Small Bites"
   - In catalogue: senior + small breed label: 25 → senior-specific with no size label (suits all sizes): 20 → any food that includes senior dogs, no size label: 121 → all life stages: 138
2. **Senior wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog senior wet food or topper
   - Look for: "Senior", "Mature", "7+", "Aging" on wet food; toppers suit any age
   - In catalogue: senior-specific wet food: 23 → any wet food that includes senior dogs: 157 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Soft treats**
   - Category: Dog > Treats > Soft & Chewy Treats
   - Search: dog soft treats
   - Look for: soft and chewy texture
   - In catalogue: soft and chewy treats: 184
   - Ask the DPL: "Does the dog prefer softer treats now?"
4. **Joint support**
   - Category: Dog > Supplies > Health & Wellness > Hip & Joint Care; Dog > Treats
   - Search: dog joint support
   - Look for: category "Hip & Joint Care"; no health claims beyond the page
   - In catalogue: hip and joint care: 35 → treats with a joint label: 60
   - Ask the DPL: "Is the dog as keen on walks as before?"
5. **Orthopedic or supportive bed**
   - Category: Dog > Supplies > Beds & Mats > Beds
   - Search: dog orthopedic or supportive bed
   - Look for: "Orthopedic" or "Memory Foam"
   - In catalogue: beds with orthopedic or memory foam wording: 15 → beds: 66
   - Ask the DPL: "Where does the dog sleep?"
6. **Elevated bowl**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls > Elevated Bowls; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog elevated bowl
   - Look for: "Elevated" bowls and feeders
   - In catalogue: elevated bowls: 12 → bowls: 68
   - Ask the DPL: "Does the dog bend down far to eat?"
7. **Gentle enrichment toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys; Dog > Supplies > Toys > Plush Toys
   - Search: dog gentle enrichment toys
   - Look for: puzzle and plush toys
   - In catalogue: interactive and puzzle toys: 99 → plush toys: 313
   - Ask the DPL: "Does the dog still like to play?"
8. **Dental care**
   - Category: Dog > Supplies > Health & Wellness > Dental & Breath Care; Dog > Treats > Dental Chews & Treats
   - Search: dog dental care
   - Look for: dental chews, water additives, toothpaste
   - In catalogue: dental and breath care: 34 → dental chews and treats: 91
   - Ask the DPL: "How are the dog's teeth?"
9. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"

### DOG · Senior · Medium

**Use when:** senior or older dog, about 7 years and up; medium dog.
**Keywords:** dog, senior, medium breed, medium dog

**Basket items, in order:**

1. **Senior dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog senior dry food
   - Look for: "Senior", "Mature", "7+", "Aging" and "Medium Breed" (rarely labelled; most medium dogs use foods with no size label)
   - In catalogue: senior + medium breed label: 2 → senior-specific with no size label (suits all sizes): 20 → any food that includes senior dogs, no size label: 121 → all life stages: 138
2. **Senior wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog senior wet food or topper
   - Look for: "Senior", "Mature", "7+", "Aging" on wet food; toppers suit any age
   - In catalogue: senior-specific wet food: 23 → any wet food that includes senior dogs: 157 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Soft treats**
   - Category: Dog > Treats > Soft & Chewy Treats
   - Search: dog soft treats
   - Look for: soft and chewy texture
   - In catalogue: soft and chewy treats: 184
   - Ask the DPL: "Does the dog prefer softer treats now?"
4. **Joint support**
   - Category: Dog > Supplies > Health & Wellness > Hip & Joint Care; Dog > Treats
   - Search: dog joint support
   - Look for: category "Hip & Joint Care"; no health claims beyond the page
   - In catalogue: hip and joint care: 35 → treats with a joint label: 60
   - Ask the DPL: "Is the dog as keen on walks as before?"
5. **Orthopedic or supportive bed**
   - Category: Dog > Supplies > Beds & Mats > Beds
   - Search: dog orthopedic or supportive bed
   - Look for: "Orthopedic" or "Memory Foam"
   - In catalogue: beds with orthopedic or memory foam wording: 15 → beds: 66
   - Ask the DPL: "Where does the dog sleep?"
6. **Elevated bowl**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls > Elevated Bowls; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog elevated bowl
   - Look for: "Elevated" bowls and feeders
   - In catalogue: elevated bowls: 12 → bowls: 68
   - Ask the DPL: "Does the dog bend down far to eat?"
7. **Gentle enrichment toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys; Dog > Supplies > Toys > Plush Toys
   - Search: dog gentle enrichment toys
   - Look for: puzzle and plush toys
   - In catalogue: interactive and puzzle toys: 99 → plush toys: 313
   - Ask the DPL: "Does the dog still like to play?"
8. **Dental care**
   - Category: Dog > Supplies > Health & Wellness > Dental & Breath Care; Dog > Treats > Dental Chews & Treats
   - Search: dog dental care
   - Look for: dental chews, water additives, toothpaste
   - In catalogue: dental and breath care: 34 → dental chews and treats: 91
   - Ask the DPL: "How are the dog's teeth?"
9. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"

### DOG · Senior · Large

**Use when:** senior or older dog, about 7 years and up; large dog.
**Keywords:** dog, senior, large breed, large dog

**Basket items, in order:**

1. **Senior dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog senior dry food
   - Look for: "Senior", "Mature", "7+", "Aging" and "Large Breed", "Giant", "Maxi"
   - In catalogue: senior + large breed label: 11 → senior-specific with no size label (suits all sizes): 20 → any food that includes senior dogs, no size label: 121 → all life stages: 138
2. **Senior wet food or topper**
   - Category: Dog > Food > Wet Food; Dog > Food > Broths & Food Toppers
   - Search: dog senior wet food or topper
   - Look for: "Senior", "Mature", "7+", "Aging" on wet food; toppers suit any age
   - In catalogue: senior-specific wet food: 23 → any wet food that includes senior dogs: 157 → broths and food toppers: 81
   - Ask the DPL: "Does the dog get any wet food or a topper with meals?"
3. **Soft treats**
   - Category: Dog > Treats > Soft & Chewy Treats
   - Search: dog soft treats
   - Look for: soft and chewy texture
   - In catalogue: soft and chewy treats: 184
   - Ask the DPL: "Does the dog prefer softer treats now?"
4. **Joint support**
   - Category: Dog > Supplies > Health & Wellness > Hip & Joint Care; Dog > Treats
   - Search: dog joint support
   - Look for: category "Hip & Joint Care"; no health claims beyond the page
   - In catalogue: hip and joint care: 35 → treats with a joint label: 60
   - Ask the DPL: "Is the dog as keen on walks as before?"
5. **Orthopedic or supportive bed**
   - Category: Dog > Supplies > Beds & Mats > Beds
   - Search: dog orthopedic or supportive bed
   - Look for: "Orthopedic" or "Memory Foam"
   - In catalogue: beds with orthopedic or memory foam wording: 15 → beds: 66
   - Ask the DPL: "Where does the dog sleep?"
6. **Elevated bowl**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls > Elevated Bowls; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog elevated bowl
   - Look for: "Elevated" bowls and feeders
   - In catalogue: elevated bowls: 12 → bowls: 68
   - Ask the DPL: "Does the dog bend down far to eat?"
7. **Gentle enrichment toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys; Dog > Supplies > Toys > Plush Toys
   - Search: dog gentle enrichment toys
   - Look for: puzzle and plush toys
   - In catalogue: interactive and puzzle toys: 99 → plush toys: 313
   - Ask the DPL: "Does the dog still like to play?"
8. **Dental care**
   - Category: Dog > Supplies > Health & Wellness > Dental & Breath Care; Dog > Treats > Dental Chews & Treats
   - Search: dog dental care
   - Look for: dental chews, water additives, toothpaste
   - In catalogue: dental and breath care: 34 → dental chews and treats: 91
   - Ask the DPL: "How are the dog's teeth?"
9. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - Look for: refill rolls or a dispenser
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on poop bags?"

## 5. Dog modifiers: activity and goal

Apply these on top of the base profile. Each one changes the food filter, adds items, or both.


### DOG · Activity · Calm

**Use when:** the dog is calm, low energy, or mostly indoors.
**Keywords:** calm dog, low energy, couch dog, indoor dog

**Basket items, in order:**

1. **Puzzle and enrichment toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys
   - Search: dog puzzle and enrichment toys
   - Look for: puzzle, treat-dispensing
   - In catalogue: interactive and puzzle toys: 99
   - Ask the DPL: "What keeps the dog busy at home?"
2. **Lick mats and slow feeders**
   - Category: Dog > Supplies; Dog > Supplies > Bowls & Feeding > Slow Feeders
   - Search: dog lick mats and slow feeders
   - Look for: "Lick" mats, slow feeders
   - In catalogue: lick mats: 23 → slow feeders: 36
   - Ask the DPL: "Would making mealtime last longer help?"
3. **Long-lasting chews**
   - Category: Dog > Treats > Bones & Chews
   - Search: dog long-lasting chews
   - Look for: bones and natural chews sized for the dog
   - In catalogue: bones and chews: 311
   - Ask the DPL: "Does the dog enjoy a chew to settle with?"

**Food:** no change to the base food. If the goal is to lose weight, apply the Lose weight modifier.

### DOG · Activity · Moderate

**Use when:** the dog gets regular daily walks and play.
**Keywords:** moderately active dog, daily walks

**Basket items, in order:**

1. **Fetch toys**
   - Category: Dog > Supplies > Toys > Balls & Fetch Toys
   - Search: dog fetch toys
   - Look for: balls, launchers, flying discs
   - In catalogue: balls and fetch toys: 76
   - Ask the DPL: "What does the dog love to chase?"
2. **Rope and tug toys**
   - Category: Dog > Supplies > Toys > Rope & Tug Toys
   - Search: dog rope and tug toys
   - Look for: rope and tug
   - In catalogue: rope and tug toys: 125
   - Ask the DPL: "Does the dog like a game of tug?"
3. **Training treats for walks**
   - Category: Dog > Treats > Training Treats
   - Search: dog training treats for walks
   - Look for: small training treats
   - In catalogue: training treats: 168
   - Ask the DPL: "Do you bring treats on walks?"

**Food:** no change to the base food.

### DOG · Activity · Very active

**Use when:** the dog is very active, sporting, working, or goes running or hiking.
**Keywords:** active dog, sporting dog, working dog, running, hiking, high energy

**Basket items, in order:**

1. **Food for active dogs**
   - Category: Dog > Food > Dry Food
   - Search: food for active dogs
   - Look for: "Sport", "Performance", "Active", "High Energy", "High Protein" in the name
   - In catalogue: dry food labelled for active or high-energy dogs: 11 → dry food labelled high protein: 10 → dry food whose description mentions active dogs or high protein: 261
   - Note: Keep the life stage and size filter from the base profile where a match exists.
2. **Freeze-dried or raw toppers**
   - Category: Dog > Food > Freeze Dried Food; Dog > Food > Broths & Food Toppers
   - Search: dog freeze-dried or raw toppers
   - Look for: freeze-dried, raw, toppers
   - In catalogue: freeze-dried food: 97 → broths and food toppers: 81
   - Ask the DPL: "Would a protein topper suit the dog's meals?"
3. **Fetch and tough toys**
   - Category: Dog > Supplies > Toys > Balls & Fetch Toys; Dog > Supplies > Toys > Tough & Durable Toys
   - Search: dog fetch and tough toys
   - Look for: launchers, balls, tough toys
   - In catalogue: balls and fetch toys: 76 → tough and durable toys: 269
   - Ask the DPL: "What does the dog do for exercise?"
4. **Water bottle and travel bowl**
   - Category: Dog > Supplies > Bowls & Feeding > Water Bottles & Travel Bowls
   - Search: dog water bottle and travel bowl
   - Look for: collapsible bowls, bottles
   - In catalogue: water bottles and travel bowls: 30
   - Ask the DPL: "Do you carry water on long outings?"
5. **Harness**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses
   - Search: dog harness
   - Look for: harness in the dog's size
   - In catalogue: harnesses: 108
   - Ask the DPL: "Does the dog pull or run with you?"

### DOG · Goal · Hold weight

**Use when:** the DPL wants to keep the dog at its current healthy weight.
**Keywords:** maintain weight, healthy weight, ideal weight

**Basket items, in order:**

1. **Training treats for portion control**
   - Category: Dog > Treats > Training Treats
   - Search: dog training treats for portion control
   - Look for: small treats so rewards stay small
   - In catalogue: training treats: 168
   - Ask the DPL: "How many treats does the dog get in a day?"
2. **Food storage and scoop**
   - Category: Dog > Supplies > Bowls & Feeding > Food Storage Containers & Accessories; Cat > Supplies > Bowls & Feeding > Food Storage Containers & Accessories
   - Search: dog food storage and scoop
   - Look for: storage containers with a scoop
   - In catalogue: food storage containers and accessories: 25
   - Ask the DPL: "How do you measure meals?"

**Food:** no change to the base food. Remind the ACE that feeding amounts are on the bag.

### DOG · Goal · Lose weight

**Use when:** the DPL says the dog needs to lose weight or eat fewer calories.
**Keywords:** overweight dog, weight loss, diet, fewer calories, light food

**Basket items, in order:**

1. **Weight management food**
   - Category: Dog > Food > Dry Food; Dog > Food > Wet Food
   - Search: dog weight management food
   - Look for: "Weight Control", "Weight Management", "Healthy Weight", "Light", "Lean", "Low Fat"
   - In catalogue: dry food with a weight label: 44 → wet food with a weight label: 16 → dry food whose description mentions weight management: 85
   - Note: Keep the life stage and size filter where a match exists. Small and large breed weight formulas are limited.
2. **Low-calorie treats**
   - Category: Dog > Treats; Dog > Treats > Training Treats
   - Search: dog low-calorie treats
   - Look for: "Skinny", "Light", "Low Calorie", or a calorie count per treat on the page
   - In catalogue: treats with a weight or low-calorie name: 11 → treats whose page gives a low calorie count: 145 → training treats (small): 168
   - Ask the DPL: "How many treats does the dog get a day?"
3. **Slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Slow Feeders
   - Search: dog slow feeder
   - Look for: slow feeder bowl
   - In catalogue: slow feeders: 36
   - Ask the DPL: "Does the dog finish meals really fast?"
4. **Puzzle toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys
   - Search: dog puzzle toys
   - Look for: treat-dispensing, puzzle
   - In catalogue: interactive and puzzle toys: 99
   - Ask the DPL: "Would a puzzle make mealtime or play more active?"

**Guardrail:** the DPL's vet should set the weight-loss target and amounts. Make no weight-loss claims.

### DOG · Goal · Gain muscle

**Use when:** the DPL wants to build or keep muscle, often for an active or working dog.
**Keywords:** muscle, high protein, bulk, working dog

**Basket items, in order:**

1. **High-protein food**
   - Category: Dog > Food > Dry Food
   - Search: dog high-protein food
   - Look for: "High Protein", "Highest Protein", "Sport", "Performance"
   - In catalogue: dry food labelled high protein or for active dogs: 21 → dry food whose description mentions high protein or muscle: 249
2. **Raw, freeze-dried or gently cooked food**
   - Category: Dog > Food > Raw Food; Dog > Food > Freeze Dried Food; Dog > Food > Dehydrated & Air Dried Food; Dog > Food > Gently Cooked Food
   - Search: dog raw, freeze-dried or gently cooked food
   - Look for: raw, freeze-dried, air-dried, gently cooked
   - In catalogue: raw, freeze-dried, air-dried and gently cooked foods: 227
   - Ask the DPL: "Have you tried adding raw or freeze-dried food?"
3. **Protein toppers**
   - Category: Dog > Food > Broths & Food Toppers
   - Search: dog protein toppers
   - Look for: broths, toppers, meal mixers
   - In catalogue: broths and food toppers: 81
   - Ask the DPL: "Would a topper help add protein to meals?"
4. **Single-protein treats**
   - Category: Dog > Treats > Freeze Dried & Dehydrated Treats
   - Search: dog single-protein treats
   - Look for: freeze-dried meat treats
   - In catalogue: freeze-dried and dehydrated treats: 117
   - Ask the DPL: "What treats does the dog get?"

**Guardrail:** if the dog is underweight or losing weight, the DPL should speak to their vet. Make no muscle-gain claims.

## 6. Foods to avoid (dogs and cats)

Our product data has no ingredient lists. It only names the main flavour, plus whatever the title and description mention. Product pages usually show the full ingredient list, and it can include ingredients the flavour does not name. For example, a lamb and rice food in our catalogue lists chicken by-product meal, beef fat, soy, corn and wheat in its ingredients.

**Rules**

- Exclude any product whose flavour, title or description names the ingredient to avoid.
- Prefer products tagged or described as free of it: the "Chicken Free" product type, "Limited Ingredients", "Grain-free", or wording such as "no corn, wheat or soy" on the page.
- Prefer limited-ingredient and single-protein recipes built on a different protein.
- Then tell the ACE to confirm the ingredient list on the product page or the bag before the DPL buys. 71 foods mention chicken in the description even though chicken is not their flavour.
- Say "this recipe doesn't list chicken in its name or description" rather than "this is chicken-free", unless the page itself says chicken-free.
- Apply the same rule to treats, toppers and dental chews, not only the main food.

**What the data shows for each ingredient** (dog and cat food and treats)

| Avoid | Named in flavour or title | Mentioned only in description | Tagged or described as free of it | How to shortlist |
|---|---|---|---|---|
| Chicken | 1,205 | 92 | 579 | Use the "Chicken Free" product type first. Also exclude "poultry". Turkey and duck are separate proteins. |
| Beef | 653 | 52 | 6 | Exclude beef, bison and buffalo flavours. No free-from tag exists. |
| Dairy | 77 | 28 | 57 | Exclude cheese, milk, yogurt and goat's milk products. |
| Wheat | 1 | 28 | 1,719 | Use "Grain-free", or pages that say no wheat. |
| Soy | 0 | 7 | 704 | Use pages that say no soy. Soy is never a named flavour. |
| Egg | 19 | 53 | 24 | Exclude egg flavours; check ingredients, egg is often an unlisted binder. |
| Lamb | 236 | 22 | 0 | Exclude lamb flavours. No free-from tag exists. |
| Fish | 845 | 171 | 17 | Exclude salmon, tuna, whitefish, herring, cod, sardine and seafood. Fish oil is common in other recipes: check ingredients. |
| Corn | 0 | 16 | 1,715 | Use "Grain-free", or pages that say no corn. |
| Grains | 574 | 603 | 1,472 | Use the "Grain-free" product type. |


### DOG · Can't eat · Chicken

**Use when:** the DPL says the dog can't have chicken, or is avoiding it.
**Keywords:** chicken allergy, chicken intolerance, no chicken, chicken-free, avoid chicken

**Basket items, in order:**

1. **Food without chicken**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Use the "Chicken Free" product type first. Also exclude "poultry". Turkey and duck are separate proteins.
   - In catalogue: dry food tagged "Chicken Free": 161 → dry food with no chicken named anywhere: 294
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without chicken**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food tagged "Chicken Free": 93
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without chicken**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats tagged "Chicken Free": 2 → treats with no chicken named: 884
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Beef

**Use when:** the DPL says the dog can't have beef, or is avoiding it.
**Keywords:** beef allergy, beef intolerance, no beef, beef-free, avoid beef

**Basket items, in order:**

1. **Food without beef**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Exclude beef, bison and buffalo flavours. No free-from tag exists.
   - In catalogue: limited-ingredient dry food with no beef named: 62 → dry food with no beef named anywhere: 473
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without beef**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no beef named anywhere: 307
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without beef**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no beef named anywhere: 763
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Dairy

**Use when:** the DPL says the dog can't have dairy, or is avoiding it.
**Keywords:** dairy allergy, dairy intolerance, no dairy, dairy-free, avoid dairy

**Basket items, in order:**

1. **Food without dairy**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Exclude cheese, milk, yogurt and goat's milk products.
   - In catalogue: limited-ingredient dry food with no dairy named: 71 → dry food with no dairy named anywhere: 547
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without dairy**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no dairy named anywhere: 419
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without dairy**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no dairy named anywhere: 992
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Wheat

**Use when:** the DPL says the dog can't have wheat, or is avoiding it.
**Keywords:** wheat allergy, wheat intolerance, no wheat, wheat-free, avoid wheat

**Basket items, in order:**

1. **Food without wheat**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Use "Grain-free", or pages that say no wheat.
   - In catalogue: grain-free dry food: 207 → dry food described as free of wheat: 289
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without wheat**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no wheat named anywhere: 419
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without wheat**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no wheat named anywhere: 1050
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Soy

**Use when:** the DPL says the dog can't have soy, or is avoiding it.
**Keywords:** soy allergy, soy intolerance, no soy, soy-free, avoid soy

**Basket items, in order:**

1. **Food without soy**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Use pages that say no soy. Soy is never a named flavour.
   - In catalogue: limited-ingredient dry food with no soy named: 70 → dry food with no soy named anywhere: 552
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without soy**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no soy named anywhere: 423
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without soy**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no soy named anywhere: 1056
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Egg

**Use when:** the DPL says the dog can't have egg, or is avoiding it.
**Keywords:** egg allergy, egg intolerance, no egg, egg-free, avoid egg

**Basket items, in order:**

1. **Food without egg**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Exclude egg flavours; check ingredients, egg is often an unlisted binder.
   - In catalogue: limited-ingredient dry food with no egg named: 70 → dry food with no egg named anywhere: 540
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without egg**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no egg named anywhere: 416
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without egg**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no egg named anywhere: 1052
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Lamb

**Use when:** the DPL says the dog can't have lamb, or is avoiding it.
**Keywords:** lamb allergy, lamb intolerance, no lamb, lamb-free, avoid lamb

**Basket items, in order:**

1. **Food without lamb**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Exclude lamb flavours. No free-from tag exists.
   - In catalogue: limited-ingredient dry food with no lamb named: 59 → dry food with no lamb named anywhere: 472
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without lamb**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no lamb named anywhere: 378
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without lamb**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no lamb named anywhere: 1010
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Fish

**Use when:** the DPL says the dog can't have fish, or is avoiding it.
**Keywords:** fish allergy, fish intolerance, no fish, fish-free, avoid fish

**Basket items, in order:**

1. **Food without fish**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Exclude salmon, tuna, whitefish, herring, cod, sardine and seafood. Fish oil is common in other recipes: check ingredients.
   - In catalogue: limited-ingredient dry food with no fish named: 46 → dry food with no fish named anywhere: 339
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without fish**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no fish named anywhere: 324
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without fish**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no fish named anywhere: 963
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### DOG · Can't eat · Corn

**Use when:** the DPL says the dog can't have corn, or is avoiding it.
**Keywords:** corn allergy, corn intolerance, no corn, corn-free, avoid corn

**Basket items, in order:**

1. **Food without corn**
   - Category: Dog > Food > Dry Food
   - Search: dog food
   - Look for: Use "Grain-free", or pages that say no corn.
   - In catalogue: grain-free dry food: 207 → dry food described as free of corn: 295
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without corn**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no corn named anywhere: 421
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without corn**
   - Category: Dog > Treats
   - Search: dog treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no corn named anywhere: 1054
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### CAT · Can't eat · Chicken

**Use when:** the DPL says the cat can't have chicken, or is avoiding it.
**Keywords:** chicken allergy, chicken intolerance, no chicken, chicken-free, avoid chicken

**Basket items, in order:**

1. **Food without chicken**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat food
   - Look for: Use the "Chicken Free" product type first. Also exclude "poultry". Turkey and duck are separate proteins.
   - In catalogue: dry food tagged "Chicken Free": 25 → dry food with no chicken named anywhere: 72
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without chicken**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food tagged "Chicken Free": 104
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without chicken**
   - Category: Cat > Food & Treats > Treats
   - Search: cat treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats tagged "Chicken Free": 0 → treats with no chicken named: 100
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### CAT · Can't eat · Beef

**Use when:** the DPL says the cat can't have beef, or is avoiding it.
**Keywords:** beef allergy, beef intolerance, no beef, beef-free, avoid beef

**Basket items, in order:**

1. **Food without beef**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat food
   - Look for: Exclude beef, bison and buffalo flavours. No free-from tag exists.
   - In catalogue: limited-ingredient dry food with no beef named: 14 → dry food with no beef named anywhere: 197
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without beef**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no beef named anywhere: 527
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without beef**
   - Category: Cat > Food & Treats > Treats
   - Search: cat treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no beef named anywhere: 155
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### CAT · Can't eat · Fish

**Use when:** the DPL says the cat can't have fish, or is avoiding it.
**Keywords:** fish allergy, fish intolerance, no fish, fish-free, avoid fish

**Basket items, in order:**

1. **Food without fish**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat food
   - Look for: Exclude salmon, tuna, whitefish, herring, cod, sardine and seafood. Fish oil is common in other recipes: check ingredients.
   - In catalogue: limited-ingredient dry food with no fish named: 7 → dry food with no fish named anywhere: 129
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without fish**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no fish named anywhere: 279
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without fish**
   - Category: Cat > Food & Treats > Treats
   - Search: cat treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no fish named anywhere: 74
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### CAT · Can't eat · Dairy

**Use when:** the DPL says the cat can't have dairy, or is avoiding it.
**Keywords:** dairy allergy, dairy intolerance, no dairy, dairy-free, avoid dairy

**Basket items, in order:**

1. **Food without dairy**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat food
   - Look for: Exclude cheese, milk, yogurt and goat's milk products.
   - In catalogue: limited-ingredient dry food with no dairy named: 14 → dry food with no dairy named anywhere: 213
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without dairy**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no dairy named anywhere: 591
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without dairy**
   - Category: Cat > Food & Treats > Treats
   - Search: cat treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no dairy named anywhere: 165
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### CAT · Can't eat · Grains

**Use when:** the DPL says the cat can't have grains, or is avoiding it.
**Keywords:** grains allergy, grains intolerance, no grains, grains-free, avoid grains

**Basket items, in order:**

1. **Food without grains**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat food
   - Look for: Use the "Grain-free" product type.
   - In catalogue: grain-free dry food: 88 → dry food described as free of grains: 68
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without grains**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no grains named anywhere: 465
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without grains**
   - Category: Cat > Food & Treats > Treats
   - Search: cat treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no grains named anywhere: 133
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

### CAT · Can't eat · Egg

**Use when:** the DPL says the cat can't have egg, or is avoiding it.
**Keywords:** egg allergy, egg intolerance, no egg, egg-free, avoid egg

**Basket items, in order:**

1. **Food without egg**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat food
   - Look for: Exclude egg flavours; check ingredients, egg is often an unlisted binder.
   - In catalogue: limited-ingredient dry food with no egg named: 13 → dry food with no egg named anywhere: 199
   - Note: Keep the life stage (and size) filter from the base profile. Confirm the ingredient list on the product page.
2. **Wet food or topper without egg**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food or topper
   - Look for: same rule as the dry food
   - In catalogue: wet food with no egg named anywhere: 577
   - Ask the DPL: "Does the pet get wet food too?"
3. **Treats without egg**
   - Category: Cat > Food & Treats > Treats
   - Search: cat treats
   - Look for: single-protein and limited-ingredient treats
   - In catalogue: treats with no egg named anywhere: 169
   - Ask the DPL: "What treats does the pet get? They need to follow the same rule."

## 7. Dog and cat needs

Apply these on top of the base profile. A product request that names one of these needs (for example "dental issues" or "joint problems") always gets the basket. Products are chosen by their labels only. For a diagnosed condition the DPL should follow their vet's advice.


### DOG · Need · Sensitive stomach

**Use when:** the DPL says the dog has a sensitive stomach or does poorly on food changes, with no active symptoms.
**Keywords:** sensitive stomach, tummy, tummy troubles, stomach issues, digestive issues, digestion, digestive, gentle food

**Basket items, in order:**

1. **Food labelled for digestive care**
   - Category: Dog > Food > Dry Food; Dog > Food > Wet Food
   - Search: dog food for digestive care
   - Look for: "Digestive Care", "Sensitive Stomach", "Sensitive Skin & Stomach", "Gentle"
   - In catalogue: dry food with the label: 152 → wet food with the label: 85 → dry food whose description mentions it: 316
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Limited-ingredient food**
   - Category: Dog > Food > Dry Food; Dog > Food > Wet Food
   - Search: dog limited-ingredient food
   - Look for: "Limited Ingredient", single protein
   - In catalogue: limited-ingredient dry food: 71 → limited-ingredient wet food: 37
   - Ask the DPL: "Are there ingredients the dog does better without?"
3. **Probiotics and digestive supplements**
   - Category: Dog > Supplies > Health & Wellness > Digestive Care
   - Search: dog probiotics and digestive supplements
   - Look for: category "Digestive Care"
   - In catalogue: digestive care: 37
   - Ask the DPL: "Lots of DPLs add a probiotic when changing food. Want to see a couple?"
4. **Single-protein treats**
   - Category: Dog > Treats > Freeze Dried & Dehydrated Treats; Dog > Treats
   - Search: dog single-protein treats
   - Look for: freeze-dried, one protein
   - In catalogue: freeze-dried and dehydrated treats: 117 → treats with a digestive label: 121
   - Ask the DPL: "What treats does the dog usually get?"
5. **Slow feeder**
   - Category: Dog > Supplies > Bowls & Feeding > Slow Feeders
   - Search: dog slow feeder
   - Look for: slow feeder bowl
   - In catalogue: slow feeders: 36
   - Ask the DPL: "Does the dog gulp its food?"

**Guardrail (only if the DPL describes these signs):** vomiting, diarrhea or blood are symptoms: refer to a vet and do not build a basket. A general sensitive-stomach request still gets the basket.

### DOG · Need · Skin & coat

**Use when:** the DPL wants to support skin and coat, or mentions dry or dull coat.
**Keywords:** skin, coat, skin issues, skin problems, coat problems, itchy, dry skin, shedding, dull coat, omega

**Basket items, in order:**

1. **Food labelled for skin and coat**
   - Category: Dog > Food > Dry Food; Dog > Food > Wet Food
   - Search: dog food for skin and coat
   - Look for: "Skin & Coat", "Sensitive Skin", "Omega"
   - In catalogue: dry food with the label: 118 → wet food with the label: 43 → dry food whose description mentions it: 272
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Skin and coat supplements**
   - Category: Dog > Supplies > Health & Wellness > Skin & Coat Care
   - Search: dog skin and coat supplements
   - Look for: category "Skin & Coat Care"; fish oils
   - In catalogue: skin and coat care: 35
   - Ask the DPL: "Do you add anything to meals for the coat?"
3. **Shampoo and conditioner**
   - Category: Dog > Supplies > Grooming > Shampoos & Conditioners
   - Search: dog shampoo and conditioner
   - Look for: gentle, oatmeal, sensitive skin
   - In catalogue: shampoos and conditioners: 51
   - Ask the DPL: "What do you bathe the dog with?"
4. **Brushes**
   - Category: Dog > Supplies > Grooming > Brushes & Combs; Dog > Supplies > Grooming > Deshedding Solutions
   - Search: dog brushes
   - Look for: brush for the coat type
   - In catalogue: brushes and combs: 32 → deshedding solutions: 17
   - Ask the DPL: "How often does the dog get brushed?"
5. **Treats with a skin and coat label**
   - Category: Dog > Treats
   - Search: dog treats skin and coat
   - Look for: salmon and fish-based treats
   - In catalogue: treats with the label: 92
   - Ask the DPL: "What treats does the dog get?"

**Guardrail (only if the DPL describes these signs):** persistent itching, sores or hair loss are symptoms: refer to a vet.

### DOG · Need · Joints

**Use when:** the DPL wants joint or mobility support, often for a large or senior dog.
**Keywords:** joints, hips, joint issues, joint problems, hip issues, mobility, arthritis, stiff, glucosamine

**Basket items, in order:**

1. **Food labelled for hip and joint**
   - Category: Dog > Food > Dry Food; Dog > Food > Wet Food
   - Search: dog food for hip and joint
   - Look for: "Hip & Joint", "Joint Care", "Mobility"
   - In catalogue: dry food with the label: 33 → wet food with the label: 17 → dry food whose description mentions it: 121
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Joint supplements**
   - Category: Dog > Supplies > Health & Wellness > Hip & Joint Care
   - Search: dog joint supplements
   - Look for: category "Hip & Joint Care"
   - In catalogue: hip and joint care: 35
   - Ask the DPL: "Is the dog as keen on walks as before?"
3. **Treats with a joint label**
   - Category: Dog > Treats
   - Search: dog treats joint
   - Look for: hip and joint treats
   - In catalogue: treats with the label: 60
   - Ask the DPL: "Would a daily joint treat be easier than a supplement?"
4. **Orthopedic bed**
   - Category: Dog > Supplies > Beds & Mats > Beds
   - Search: dog orthopedic bed
   - Look for: "Orthopedic", "Memory Foam"
   - In catalogue: beds with orthopedic or memory foam wording: 15 → beds: 66
   - Ask the DPL: "Where does the dog sleep?"
5. **Elevated bowl**
   - Category: Dog > Supplies > Bowls & Feeding > Bowls > Elevated Bowls
   - Search: dog elevated bowl
   - Look for: elevated feeders
   - In catalogue: elevated bowls: 12
   - Ask the DPL: "Does the dog bend down far to eat?"

**Guardrail (only if the DPL describes these signs):** limping or pain is a symptom: refer to a vet.

### DOG · Need · Dental

**Use when:** the DPL wants products for the dog's teeth, tartar or breath, including requests for "dental issues" or "dental problems".
**Keywords:** teeth, dental, dental issues, dental problems, teeth cleaning, tartar, plaque, bad breath, oral care, dental food

**Basket items, in order:**

1. **Dental chews and treats**
   - Category: Dog > Treats > Dental Chews & Treats
   - Search: dog dental chews and treats
   - Look for: sized for the dog's weight
   - In catalogue: dental chews and treats: 91
   - Ask the DPL: "Does the dog get a daily dental chew?"
2. **Dental and breath care**
   - Category: Dog > Supplies > Health & Wellness > Dental & Breath Care
   - Search: dog dental and breath care
   - Look for: toothpaste, brushes, water additives, gels
   - In catalogue: dental and breath care: 34
   - Ask the DPL: "Have you tried brushing or a water additive?"
3. **Dental chew toys**
   - Category: Dog > Supplies > Toys; Dog > Supplies > Toys > Chew Toys
   - Search: dog dental chew toys
   - Look for: "Dental" toys
   - In catalogue: toys with a dental label: 92 → chew toys: 87
   - Ask the DPL: "Does the dog like to chew toys?"
4. **Food with a dental label**
   - Category: Dog > Food > Dry Food
   - Search: dog food dental
   - Look for: "Dental", "Oral Care"
   - In catalogue: dry food with the label: 11
   - Ask the DPL: "Would a dental kibble suit the dog?"

**Guardrail (only if the DPL describes these signs):** persistent bad breath, bleeding gums or loose teeth: refer to a vet.

### DOG · Need · Nervous or anxious

**Use when:** the dog is nervous in storms, car rides, or when left alone.
**Keywords:** anxious, nervous, anxiety, anxiety issues, storms, fireworks, separation, calming

**Basket items, in order:**

1. **Calming aids**
   - Category: Dog > Supplies > Health & Wellness > Calming & Anxiety; Dog > Supplies > Carriers & Travel Accessories > Travel Aids
   - Search: dog calming aids
   - Look for: category "Calming & Anxiety"; chews, sprays, diffusers, vests
   - In catalogue: calming and anxiety: 23 → travel aids: 20
   - Ask the DPL: "When does the dog seem most unsettled?"
2. **Lick mats and long-lasting chews**
   - Category: Dog > Supplies; Dog > Treats > Bones & Chews
   - Search: dog lick mats and long-lasting chews
   - Look for: lick mats, chews
   - In catalogue: lick mats: 23 → bones and chews: 311
   - Ask the DPL: "Does the dog settle with something to lick or chew?"
3. **Calming or covered bed**
   - Category: Dog > Supplies > Beds & Mats > Beds
   - Search: dog calming or covered bed
   - Look for: "Calming" beds, bolster or donut shapes
   - In catalogue: beds with calming wording: 24 → beds: 66
   - Ask the DPL: "Does the dog have a cozy spot of its own?"
4. **Puzzle toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys
   - Search: dog puzzle toys
   - Look for: treat-dispensing, puzzle
   - In catalogue: interactive and puzzle toys: 99
   - Ask the DPL: "What keeps the dog busy when alone?"
5. **Crate**
   - Category: Dog > Supplies > Crates, Pens & Gates > Crates & Pens
   - Search: dog crate
   - Look for: crate with a pad
   - In catalogue: crates and pens: 11
   - Ask the DPL: "Does the dog have a den-like space?"

**Guardrail (only if the DPL describes these signs):** for severe anxiety or aggression, suggest the DPL speak to their vet.

### DOG · Need · Food sensitivities

**Use when:** the DPL mentions food sensitivities or wants a limited-ingredient diet.
**Keywords:** food sensitivities, food allergies, allergy, allergy issues, limited ingredient, LID, novel protein, single protein, hypoallergenic

**Basket items, in order:**

1. **Limited-ingredient or sensitivities food**
   - Category: Dog > Food > Dry Food; Dog > Food > Wet Food
   - Search: dog limited-ingredient or sensitivities food
   - Look for: "Limited Ingredient", "Food Sensitivities", single or novel protein
   - In catalogue: limited-ingredient dry food: 71 → dry food labelled for food sensitivities: 100 → limited-ingredient wet food: 37
2. **Single-protein treats**
   - Category: Dog > Treats > Freeze Dried & Dehydrated Treats
   - Search: dog single-protein treats
   - Look for: one protein, freeze-dried
   - In catalogue: freeze-dried and dehydrated treats: 117
   - Ask the DPL: "What treats does the dog get?"
3. **Food storage**
   - Category: Dog > Supplies > Bowls & Feeding > Food Storage Containers & Accessories; Cat > Supplies > Bowls & Feeding > Food Storage Containers & Accessories
   - Search: dog food storage
   - Look for: sealed container
   - In catalogue: food storage containers and accessories: 25
   - Ask the DPL: "How do you keep the food fresh and separate?"

Combine with the matching Can't eat profile in section 6 when the DPL names the ingredient.

### DOG · Need · Urinary

**Use when:** the DPL asks for urinary support products.
**Keywords:** urinary, urinary issues, urinary problems, bladder, UT

**Basket items, in order:**

1. **Urinary care supplements**
   - Category: Dog > Supplies > Health & Wellness > Urinary Care
   - Search: dog urinary care supplements
   - Look for: category "Urinary Care"
   - In catalogue: urinary care: 8
   - Ask the DPL: "Does the dog drink plenty of water?"
2. **Wet food for moisture**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food for moisture
   - Look for: wet food adds moisture
   - In catalogue: wet food: 424
   - Ask the DPL: "Does the dog get any wet food?"

**Guardrail (only if the DPL describes these signs):** straining, blood in urine or frequent accidents: refer to a vet immediately. Never recommend prescription urinary diets.

## 8. Cat base profiles (age)

Pick one base profile from the cat's age, then add modifiers from sections 6 and 9. Cat size (small, average, large) does not change which products apply: our catalogue has no size-labelled cat food. Use the weight goal instead.


### CAT · Kitten

**Use when:** new kitten, kitten under 1 year.
**Keywords:** cat, kitten

**Basket items, in order:**

1. **Kitten dry food**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat kitten dry food
   - Look for: "Kitten"
   - In catalogue: kitten-specific dry food: 24 → any dry food that includes kittens: 72 → all life stages dry food: 49
2. **Kitten wet food**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat kitten wet food
   - Look for: cans, pouches, cups; pâté or chunks
   - In catalogue: kitten-specific wet food: 35 → any wet food that includes kittens: 215 → all life stages wet food: 189
   - Ask the DPL: "Does the cat get wet food as well as dry?"
3. **Litter box and litter**
   - Category: Cat > Litter & Accessories > Litter Boxes; Cat > Litter & Accessories > Litter
   - Search: cat litter box and litter
   - Look for: low-sided pan for kittens; unscented litter
   - In catalogue: litter boxes: 32 → litter: 70
   - Ask the DPL: "Does the kitten have a litter box set up?"
4. **Scratcher**
   - Category: Cat > Supplies > Furniture & Scratchers > Scratchers & Posts
   - Search: cat scratcher
   - Look for: posts, corrugate scratchers
   - In catalogue: scratchers and posts: 37
   - Ask the DPL: "Does the kitten have somewhere to scratch?"
5. **Wand and small toys**
   - Category: Cat > Supplies > Toys > Teasers & Wands; Cat > Supplies > Toys > Ball Toys
   - Search: cat wand and small toys
   - Look for: teasers, wands, small balls
   - In catalogue: teasers and wands: 38 → ball toys: 26
   - Ask the DPL: "What does the kitten like to pounce on?"
6. **Bowls or fountain**
   - Category: Cat > Supplies > Bowls & Feeding > Bowls; Cat > Supplies > Bowls & Feeding > Feeders & Waterers
   - Search: cat bowls or fountain
   - Look for: shallow bowls, fountain
   - In catalogue: bowls: 56 → feeders and waterers: 28
   - Ask the DPL: "Does the kitten have its own bowls?"
7. **Carrier**
   - Category: Cat > Supplies > Carriers & Travel Accessories
   - Search: cat carrier
   - Look for: carrier sized for an adult cat
   - In catalogue: carriers: 47
   - Ask the DPL: "Do you have a carrier for vet visits?"
8. **Kitten treats**
   - Category: Cat > Food & Treats > Treats; Cat > Food & Treats > Broths & Food Toppers; Cat > Food & Treats > Treats > Soft & Chewy Treats
   - Search: cat kitten treats
   - Look for: soft or lickable treats
   - In catalogue: treats labelled for kittens: 28 → soft and chewy treats: 37
   - Ask the DPL: "Any treats for bonding and training?"

### CAT · Adult

**Use when:** adult cat, about 1 to 7 years (some brands to 10).
**Keywords:** cat, adult

**Basket items, in order:**

1. **Adult dry food**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat adult dry food
   - Look for: "Adult"
   - In catalogue: adult-specific dry food: 136 → any dry food that includes adult cats: 185 → all life stages dry food: 49
2. **Adult wet food**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat adult wet food
   - Look for: cans, pouches, cups; pâté or chunks
   - In catalogue: adult-specific wet food: 370 → any wet food that includes adult cats: 551 → all life stages wet food: 189
   - Ask the DPL: "Does the cat get wet food as well as dry?"
3. **Litter**
   - Category: Cat > Litter & Accessories > Litter
   - Search: cat litter
   - Look for: clumping, clay, natural (corn, wheat, pine, walnut), silica
   - In catalogue: litter: 70
   - Ask the DPL: "Running low on litter?"
4. **Treats**
   - Category: Cat > Food & Treats > Treats > Crunchy Treats; Cat > Food & Treats > Treats > Soft & Chewy Treats; Cat > Food & Treats > Treats > Freeze Dried & Dehydrated Treats
   - Search: cat treats
   - Look for: crunchy, soft, freeze-dried, lickable
   - In catalogue: crunchy treats: 34 → soft and chewy treats: 37 → freeze-dried treats: 50
   - Ask the DPL: "What treats does the cat like?"
5. **Scratcher or cat tree**
   - Category: Cat > Supplies > Furniture & Scratchers > Scratchers & Posts; Cat > Supplies > Furniture & Scratchers > Trees & Condos
   - Search: scratcher or cat tree
   - Look for: posts, trees, condos
   - In catalogue: scratchers and posts: 37 → trees and condos: 41
   - Ask the DPL: "Does the cat have somewhere to scratch and climb?"
6. **Toys**
   - Category: Cat > Supplies > Toys > Teasers & Wands; Cat > Supplies > Toys > Lasers & Interactive Toys; Cat > Supplies > Toys > Catnip & Grass
   - Search: cat toys
   - Look for: wands, interactive, catnip
   - In catalogue: teasers and wands: 38 → lasers and interactive toys: 69 → catnip and grass: 33
   - Ask the DPL: "How does the cat like to play?"
7. **Fountain or bowls**
   - Category: Cat > Supplies > Bowls & Feeding > Feeders & Waterers; Cat > Supplies > Bowls & Feeding > Bowls
   - Search: cat fountain or bowls
   - Look for: fountains encourage drinking
   - In catalogue: feeders and waterers: 28 → bowls: 56
   - Ask the DPL: "Does the cat drink much water?"

### CAT · Senior

**Use when:** senior cat, about 7 years and up.
**Keywords:** cat, senior

**Basket items, in order:**

1. **Senior dry food**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat senior dry food
   - Look for: "Senior", "Mature", "7+", "Aging"
   - In catalogue: senior-specific dry food: 16 → any dry food that includes senior cats: 65 → all life stages dry food: 49
2. **Senior wet food**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat senior wet food
   - Look for: cans, pouches, cups; pâté or chunks
   - In catalogue: senior-specific wet food: 19 → any wet food that includes senior cats: 221 → all life stages wet food: 189
   - Ask the DPL: "Does the cat get wet food as well as dry?"
3. **Litter and an easy-entry box**
   - Category: Cat > Litter & Accessories > Litter Boxes; Cat > Litter & Accessories > Litter
   - Search: cat litter and an easy-entry box
   - Look for: low-entry pan; soft, low-dust litter
   - In catalogue: litter boxes described as low entry or senior friendly: 5 → litter pans: 14 → litter: 70
   - Ask the DPL: "Is the litter box easy for the cat to step into?"
4. **Soft or lickable treats**
   - Category: Cat > Food & Treats > Broths & Food Toppers; Cat > Food & Treats > Treats > Soft & Chewy Treats
   - Search: cat soft or lickable treats
   - Look for: lickable purées, broths, soft treats
   - In catalogue: broths and food toppers: 90 → soft and chewy treats: 37
   - Ask the DPL: "Does the cat prefer softer treats now?"
5. **Joint support**
   - Category: Cat > Supplies > Health & Wellness > Hip & Joint Care
   - Search: cat joint support
   - Look for: category "Hip & Joint Care"
   - In catalogue: hip and joint care: 21
   - Ask the DPL: "Is the cat still jumping up to favourite spots?"
6. **Warm, supportive bed**
   - Category: Cat > Supplies > Beds
   - Search: cat warm, supportive bed
   - Look for: soft beds, heated or self-warming
   - In catalogue: beds: 28
   - Ask the DPL: "Where does the cat like to nap?"
7. **Fountain**
   - Category: Cat > Supplies > Bowls & Feeding > Feeders & Waterers
   - Search: cat fountain
   - Look for: fountains encourage drinking
   - In catalogue: feeders and waterers: 28
   - Ask the DPL: "Does the cat drink much water?"

## 9. Cat modifiers: lifestyle, goal and needs


### CAT · Lifestyle · Indoor only

**Use when:** the cat lives indoors only.
**Keywords:** indoor cat, apartment cat, house cat

**Basket items, in order:**

1. **Indoor formula food**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat indoor formula food
   - Look for: "Indoor" in the name
   - In catalogue: dry food labelled indoor: 19 → wet food labelled indoor: 14
2. **Interactive toys**
   - Category: Cat > Supplies > Toys > Teasers & Wands; Cat > Supplies > Toys > Lasers & Interactive Toys
   - Search: cat interactive toys
   - Look for: wands, lasers, interactive
   - In catalogue: teasers and wands: 38 → lasers and interactive toys: 69
   - Ask the DPL: "How does the cat get exercise indoors?"
3. **Cat tree or window perch**
   - Category: Cat > Supplies > Furniture & Scratchers > Trees & Condos
   - Search: cat tree or window perch
   - Look for: trees, condos, perches
   - In catalogue: trees and condos: 41
   - Ask the DPL: "Does the cat have a spot to climb or look outside?"
4. **Cat grass and catnip**
   - Category: Cat > Supplies > Toys > Catnip & Grass
   - Search: cat grass and catnip
   - Look for: cat grass kits, catnip
   - In catalogue: catnip and grass: 33
   - Ask the DPL: "Does the cat chew on houseplants?"
5. **Hairball support**
   - Category: Cat > Supplies > Health & Wellness > Hairball Control; Cat > Food & Treats > Dry Food
   - Search: cat hairball support
   - Look for: "Hairball" food, treats or gel
   - In catalogue: hairball control: 7 → dry food labelled hairball: 15
   - Ask the DPL: "Does the cat get hairballs?"

### CAT · Lifestyle · Indoor and outdoor, or mostly outdoor

**Use when:** the cat goes outside some or most of the time.
**Keywords:** outdoor cat, indoor outdoor cat, goes outside

**Basket items, in order:**

1. **Collar and ID tag**
   - Category: Cat > Supplies > Collars, Leashes & Harnesses > Collars; Cat > Supplies > Collars, Leashes & Harnesses > ID Tags & Accessories
   - Search: cat collar and id tag
   - Look for: breakaway collar, ID tag, reflective
   - In catalogue: collars: 40 → ID tags and accessories: 104
   - Ask the DPL: "Does the cat wear a collar with ID?"
2. **Flea and tick protection**
   - Category: Cat > Supplies > Flea & Tick
   - Search: cat flea and tick protection
   - Look for: cat-specific products only; follow the label weight range
   - In catalogue: cat flea and tick: 23
   - Ask the DPL: "Is the cat protected for flea and tick season?"
3. **Harness and leash**
   - Category: Cat > Supplies > Collars, Leashes & Harnesses > Leashes & Harnesses
   - Search: cat harness and leash
   - Look for: cat harness
   - In catalogue: leashes and harnesses: 29
   - Ask the DPL: "Would supervised outdoor time on a harness suit the cat?"
4. **Higher-protein food**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat higher-protein food
   - Look for: high protein, grain-free
   - In catalogue: dry food labelled high protein: 11 → grain-free dry food: 88
   - Ask the DPL: "Is the cat very active outdoors?"

**Guardrail:** never suggest a dog flea product for a cat. Follow the label only; no dosing advice.

### CAT · Goal · Hold weight

**Use when:** the DPL wants to keep the cat at its current healthy weight.
**Keywords:** maintain weight, healthy weight

**Basket items, in order:**

1. **Slow feeder or puzzle feeder**
   - Category: Cat > Supplies > Bowls & Feeding > Slow Feeders
   - Search: cat slow feeder or puzzle feeder
   - Look for: slow feeders, puzzle feeders
   - In catalogue: slow feeders: 20
   - Ask the DPL: "Does the cat eat quickly or graze all day?"
2. **Active play toys**
   - Category: Cat > Supplies > Toys > Teasers & Wands
   - Search: cat active play toys
   - Look for: wands, interactive
   - In catalogue: teasers and wands: 38
   - Ask the DPL: "How much play does the cat get each day?"

**Food:** no change to the base food.

### CAT · Goal · Lose weight

**Use when:** the DPL says the cat needs to lose weight.
**Keywords:** overweight cat, weight loss, diet

**Basket items, in order:**

1. **Weight management food**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat weight management food
   - Look for: "Weight Control", "Healthy Weight", "Weight Care", "Light", "Lean"
   - In catalogue: dry food with a weight label: 22 → wet food with a weight label: 27
2. **Slow feeder or puzzle feeder**
   - Category: Cat > Supplies > Bowls & Feeding > Slow Feeders
   - Search: cat slow feeder or puzzle feeder
   - Look for: slow feeders
   - In catalogue: slow feeders: 20
   - Ask the DPL: "Would a puzzle feeder slow mealtime down?"
3. **Active play toys**
   - Category: Cat > Supplies > Toys > Lasers & Interactive Toys; Cat > Supplies > Toys > Teasers & Wands
   - Search: cat active play toys
   - Look for: wands, lasers, interactive
   - In catalogue: lasers and interactive toys: 69 → teasers and wands: 38
   - Ask the DPL: "How much play does the cat get each day?"
4. **Low-calorie treats**
   - Category: Cat > Food & Treats > Treats; Cat > Food & Treats > Broths & Food Toppers; Cat > Food & Treats > Treats > Freeze Dried & Dehydrated Treats
   - Search: cat low-calorie treats
   - Look for: freeze-dried single protein; lickable treats in small amounts
   - In catalogue: treats with a weight label: 10 → freeze-dried treats: 50
   - Ask the DPL: "How many treats does the cat get?"

**Guardrail:** the DPL's vet should set the weight-loss target. Rapid weight loss is dangerous for cats.

### CAT · Need · Hairballs

**Use when:** the DPL asks about hairballs for the cat.
**Keywords:** hairball, hairballs, hairball issues, long hair, shedding

**Basket items, in order:**

1. **Food labelled for hairball control**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat food for hairball control
   - Look for: "Hairball" in the name
   - In catalogue: dry food with the label: 15 → wet food with the label: 9 → dry food whose description mentions it: 25
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Hairball remedies**
   - Category: Cat > Supplies > Health & Wellness > Hairball Control
   - Search: cat hairball remedies
   - Look for: category "Hairball Control"; gels, chews
   - In catalogue: hairball control: 7
   - Ask the DPL: "How often does the cat bring up hairballs?"
3. **Brush or deshedding tool**
   - Category: Cat > Supplies > Grooming > Grooming Tools
   - Search: cat brush or deshedding tool
   - Look for: brushes, combs, deshedding
   - In catalogue: grooming tools: 27
   - Ask the DPL: "How often is the cat brushed?"
4. **Hairball treats**
   - Category: Cat > Food & Treats > Treats; Cat > Food & Treats > Broths & Food Toppers
   - Search: cat hairball treats
   - Look for: hairball treats
   - In catalogue: treats with a hairball label: 5
   - Ask the DPL: "Would a daily hairball treat be easier?"

**Guardrail (only if the DPL describes these signs):** frequent vomiting is a symptom: refer to a vet.

### CAT · Need · Urinary support

**Use when:** the DPL asks about urinary support for the cat.
**Keywords:** urinary, urinary issues, urinary problems, bladder, UT, crystals

**Basket items, in order:**

1. **Food labelled for urinary care**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat food for urinary care
   - Look for: "Urinary", "Urinary Care", "Urinary Tract Health"
   - In catalogue: dry food with the label: 7 → wet food with the label: 23 → dry food whose description mentions it: 30
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Wet food for moisture**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food for moisture
   - Look for: wet food adds moisture
   - In catalogue: wet food with a urinary label: 23 → wet food: 602
   - Ask the DPL: "Does the cat eat wet food daily?"
3. **Water fountain**
   - Category: Cat > Supplies > Bowls & Feeding > Feeders & Waterers
   - Search: cat water fountain
   - Look for: fountains
   - In catalogue: feeders and waterers with fountain wording: 17 → feeders and waterers: 28
   - Ask the DPL: "Does the cat drink much water? Some cats prefer a fountain."
4. **Urinary care supplements**
   - Category: Cat > Supplies > Health & Wellness > Urinary Care
   - Search: cat urinary care supplements
   - Look for: category "Urinary Care"
   - In catalogue: urinary care: 10
   - Ask the DPL: "Has the vet suggested anything for urinary health?"

**Guardrail (only if the DPL describes these signs):** straining, blood in urine, or a cat that cannot pee is an emergency: tell the ACE the DPL should contact a vet immediately. Never recommend prescription urinary diets.

### CAT · Need · Sensitive stomach

**Use when:** the DPL asks about sensitive stomach for the cat.
**Keywords:** sensitive stomach, stomach issues, digestive issues, digestion, tummy

**Basket items, in order:**

1. **Food labelled for digestive care**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat food for digestive care
   - Look for: "Digestive Care", "Sensitive Stomach", "Digest Sensitive"
   - In catalogue: dry food with the label: 69 → wet food with the label: 90 → dry food whose description mentions it: 118
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Limited-ingredient food**
   - Category: Cat > Food & Treats > Wet Food; Cat > Food & Treats > Dry Food
   - Search: cat limited-ingredient food
   - Look for: "Limited Ingredient"
   - In catalogue: limited-ingredient wet food: 38 → limited-ingredient dry food: 14
   - Ask the DPL: "Are there ingredients the cat does better without?"
3. **Probiotics and digestive care**
   - Category: Cat > Supplies > Health & Wellness > Probiotics & Digestive Care
   - Search: cat probiotics and digestive care
   - Look for: category "Probiotics & Digestive Care"
   - In catalogue: probiotics and digestive care: 29
   - Ask the DPL: "Lots of DPLs add a probiotic when changing food. Want to see one?"
4. **Single-protein treats**
   - Category: Cat > Food & Treats > Treats > Freeze Dried & Dehydrated Treats
   - Search: cat single-protein treats
   - Look for: freeze-dried, one protein
   - In catalogue: freeze-dried treats: 50
   - Ask the DPL: "What treats does the cat get?"

**Guardrail (only if the DPL describes these signs):** vomiting or diarrhea are symptoms: refer to a vet.

### CAT · Need · Dental

**Use when:** the DPL wants products for the cat's teeth, tartar or breath, including requests for "dental issues" or "dental problems".
**Keywords:** teeth, dental, dental issues, dental problems, tartar, breath, dental treats

**Basket items, in order:**

1. **Food labelled for dental care**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat food for dental care
   - Look for: "Dental", "Oral Care"
   - In catalogue: dry food with the label: 11 → wet food with the label: 0 → dry food whose description mentions it: 22
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Dental treats**
   - Category: Cat > Food & Treats > Treats; Cat > Food & Treats > Treats > Crunchy Treats
   - Search: cat dental treats
   - Look for: crunchy dental treats
   - In catalogue: treats with a dental label: 10 → crunchy treats: 34
   - Ask the DPL: "Does the cat get dental treats?"
3. **Dental and breath care**
   - Category: Cat > Supplies > Health & Wellness > Dental & Breath Care
   - Search: cat dental and breath care
   - Look for: category "Dental & Breath Care"
   - In catalogue: dental and breath care: 20
   - Ask the DPL: "Have you tried a water additive or brushing?"

**Guardrail (only if the DPL describes these signs):** bad breath, drooling or trouble eating: refer to a vet.

### CAT · Need · Skin & coat

**Use when:** the DPL asks about skin & coat for the cat.
**Keywords:** skin, coat, skin issues, skin problems, dandruff, dull coat

**Basket items, in order:**

1. **Food labelled for skin and coat**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat food for skin and coat
   - Look for: "Skin & Coat", "Sensitive Skin"
   - In catalogue: dry food with the label: 52 → wet food with the label: 43 → dry food whose description mentions it: 114
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Skin and coat supplements**
   - Category: Cat > Supplies > Health & Wellness > Skin & Coat Care
   - Search: cat skin and coat supplements
   - Look for: category "Skin & Coat Care"
   - In catalogue: skin and coat care: 18
   - Ask the DPL: "Do you add anything to meals for the coat?"
3. **Brush**
   - Category: Cat > Supplies > Grooming > Grooming Tools
   - Search: cat brush
   - Look for: brushes and combs
   - In catalogue: grooming tools: 27
   - Ask the DPL: "How often is the cat brushed?"

**Guardrail (only if the DPL describes these signs):** persistent itching, sores or hair loss: refer to a vet.

### CAT · Need · Joints

**Use when:** the DPL asks about joints for the cat.
**Keywords:** joints, joint issues, joint problems, mobility, arthritis, stiff

**Basket items, in order:**

1. **Food labelled for hip and joint**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat food for hip and joint
   - Look for: "Hip & Joint", "Mobility"
   - In catalogue: dry food with the label: 5 → wet food with the label: 3 → dry food whose description mentions it: 14
   - Note: Keep the life stage (and size) filter from the base profile where a match exists.
2. **Joint supplements**
   - Category: Cat > Supplies > Health & Wellness > Hip & Joint Care
   - Search: cat joint supplements
   - Look for: category "Hip & Joint Care"
   - In catalogue: hip and joint care: 21
   - Ask the DPL: "Is the cat still jumping up to favourite spots?"
3. **Easy-entry litter box**
   - Category: Cat > Litter & Accessories > Litter Boxes
   - Search: cat easy-entry litter box
   - Look for: low-entry pans
   - In catalogue: litter pans: 14
   - Ask the DPL: "Is the litter box easy to step into?"
4. **Soft bed**
   - Category: Cat > Supplies > Beds
   - Search: cat soft bed
   - Look for: soft, warm beds
   - In catalogue: beds: 28
   - Ask the DPL: "Where does the cat sleep?"

**Guardrail (only if the DPL describes these signs):** limping or pain: refer to a vet.

### CAT · Need · Nervous or anxious

**Use when:** the cat is nervous with travel, vet visits, visitors, or changes at home.
**Keywords:** anxious cat, nervous, stress, vet visit, travel, calming

**Basket items, in order:**

1. **Calming aids**
   - Category: Cat > Supplies > Health & Wellness > Calming & Anxiety
   - Search: cat calming aids
   - Look for: category "Calming & Anxiety"; diffusers, sprays, treats
   - In catalogue: calming and anxiety: 10
   - Ask the DPL: "When does the cat seem most unsettled?"
2. **Carrier**
   - Category: Cat > Supplies > Carriers & Travel Accessories
   - Search: cat carrier
   - Look for: sturdy carrier
   - In catalogue: carriers: 47
   - Ask the DPL: "Is the carrier a comfortable, familiar place?"
3. **Hiding and climbing spots**
   - Category: Cat > Supplies > Furniture & Scratchers > Trees & Condos; Cat > Supplies > Toys > Tunnels; Cat > Supplies > Beds
   - Search: cat hiding and climbing spots
   - Look for: condos, tunnels, covered beds
   - In catalogue: trees and condos: 41 → tunnels: 10 → beds: 28
   - Ask the DPL: "Does the cat have a safe place to retreat to?"

**Guardrail (only if the DPL describes these signs):** hiding with not eating, or sudden behaviour change: refer to a vet.

## 10. Breed profiles

We carry breed-specific food for the breeds below (Royal Canin breed lines). When a DPL names one of these breeds, lead the food category with the breed formula for the pet's age, then use the base profile for everything else. For any other breed, use the base profile for its size.

### CAT · Breed · Bengal

**Use when:** the DPL names a Bengal.
**Breed-specific food we carry:**
- Royal Canin Feline Breed Nurtition Bengal Adult Cat Food (FCM04653): dry; life stage Adult

### DOG · Breed · Boxer

**Use when:** the DPL names a Boxer. Base profile size: Large.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Boxer Adult Dog Food (FCM00256): dry; life stage Adult
- Royal Canin Breed Health Nutrition Boxer Puppy Dog Food (FCM04177): dry; life stage Puppy

### DOG · Breed · Bulldog

**Use when:** the DPL names a Bulldog. Base profile size: Medium.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Bulldog Adult Dog Food (FCM02661): dry; life stage Adult
- Royal Canin Breed Health Nutrition Bulldog Puppy Dog Food (FCM00257): dry; life stage Puppy

### DOG · Breed · Cavalier King Charles

**Use when:** the DPL names a Cavalier King Charles. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Cavalier King Charles Adult Dog Food (FCM09245): dry; life stage Adult, Senior
- Royal Canin Breed Health Nutrition Cavalier King Charles Puppy Dog Food (FCM09247): dry; life stage Puppy

### DOG · Breed · Chihuahua

**Use when:** the DPL names a Chihuahua. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Chihuahua Adult Dog Food (FCM00258): dry; life stage Adult
- Royal Canin Breed Health Nutrition Chihuahua Loaf In Sauce Adult Dog Food (FCM05403): wet; life stage Adult
- Royal Canin Breed Health Nutrition Chihuahua Puppy Dog Food (FCM02660): dry; life stage Puppy

### DOG · Breed · Dachshund

**Use when:** the DPL names a Dachshund. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Dachshund Adult Dog Food (FCM00259): dry; life stage Adult
- Royal Canin Breed Health Nutrition Dachshund Loaf in Sauce Adult Dog Food (FCM04987): wet; life stage Adult
- Royal Canin Breed Health Nutrition Dachshund Puppy Dog Food (FCM04652): dry; life stage Puppy

### DOG · Breed · French Bulldog

**Use when:** the DPL names a French Bulldog. Base profile size: Small or Medium.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition French Bulldog Adult Dog Food (FCM00882): dry; life stage Adult
- Royal Canin Breed Health Nutrition French Bulldog Loaf in Sauce Adult Dog Food (FCM09241): wet; life stage Adult, Senior
- Royal Canin Breed Health Nutrition French Bulldog Puppy Dog Food (FCM06888): dry; life stage Puppy

### DOG · Breed · German Shepherd

**Use when:** the DPL names a German Shepherd. Base profile size: Large.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition German Shepherd Adult Dog Food (FCM00260): dry; life stage Adult
- Royal Canin Breed Health Nutrition German Shepherd Loaf in Sauce Adult Dog Food (FCM08896): wet; life stage Adult
- Royal Canin Breed Health Nutrition German Shepherd Puppy Dog Food (FCM05404): dry; life stage Puppy

### DOG · Breed · Golden Retriever

**Use when:** the DPL names a Golden Retriever. Base profile size: Large.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Golden Retriever Adult Dog Food (FCM05405): dry; life stage Adult
- Royal Canin Breed Health Nutrition Golden Retriever Loaf in Sauce Adult Dog Food (FCM08895): wet; life stage Adult
- Royal Canin Breed Health Nutrition Golden Retriever Puppy Dog Food (FCM06048): dry; life stage Puppy

### DOG · Breed · Labrador Retriever

**Use when:** the DPL names a Labrador Retriever. Base profile size: Large.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Labrador Retriever Adult Dog Food (FCM01319): dry; life stage Adult
- Royal Canin Breed Health Nutrition Labrador Retriever Loaf In Sauce Adult Dog Food (FCM08897): wet; life stage Adult
- Royal Canin Breed Health Nutrition Labrador Retriever Puppy Dog Food (FCM06482): dry; life stage Puppy

### CAT · Breed · Maine Coon

**Use when:** the DPL names a Maine Coon.
**Breed-specific food we carry:**
- Royal Canin Feline Breed Nutrition Maine Coon Adult Cat Food (FCM05410): dry; life stage Adult

### DOG · Breed · Miniature Schnauzer

**Use when:** the DPL names a Miniature Schnauzer. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Miniature Schnauzer Adult Dog Food (FCM05412): dry; life stage Adult
- Royal Canin Breed Health Nutrition Miniature Schnauzer Puppy Dog Food (FCM06886): dry; life stage Puppy

### CAT · Breed · Persian

**Use when:** the DPL names a Persian.
**Breed-specific food we carry:**
- Royal Canin Feline Breed Nutrition Persian Adult Cat Food (FCM00252): dry; life stage Adult
- Royal Canin Persian Kitten Cat Food (FCM08949): dry; life stage Kitten

### DOG · Breed · Poodle

**Use when:** the DPL names a Poodle. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Poodle Adult Dog Food (FCM00262): dry; life stage Adult
- Royal Canin Breed Health Nutrition Poodle Loaf in Sauce Adult Dog Food (FCM04986): wet; life stage Adult
- Royal Canin Breed Health Nutrition Poodle Puppy Dog Food (FCM04317): dry; life stage Puppy

### DOG · Breed · Pug

**Use when:** the DPL names a Pug. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Pug Adult Dog Food (FCM01025): dry; life stage Adult
- Royal Canin Breed Health Nutrition Pug Puppy Dog Food (FCM06887): dry; life stage Puppy

### CAT · Breed · Ragdoll

**Use when:** the DPL names a Ragdoll.
**Breed-specific food we carry:**
- Royal Canin Ragdoll Adult Cat Food (FCM08954): dry; life stage Adult

### DOG · Breed · Rottweiler

**Use when:** the DPL names a Rottweiler. Base profile size: Large.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Rottweiler Adult Dog Food (FCM00263): dry; life stage Adult

### DOG · Breed · Shih Tzu

**Use when:** the DPL names a Shih Tzu. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Shih Tzu Adult Dog Food (FCM00264): dry; life stage Adult
- Royal Canin Breed Health Nutrition Shih Tzu Loaf In Sauce Dog Food (FCM05415): wet; life stage Adult
- Royal Canin Breed Health Nutrition Shih Tzu Puppy Dog Food (FCM05416): dry; life stage Puppy

### CAT · Breed · Siamese

**Use when:** the DPL names a Siamese.
**Breed-specific food we carry:**
- Royal Canin Feline Breed Nutrition Siamese Adult Cat Food (FCM07392): dry; life stage Adult, Senior

### CAT · Breed · Sphynx

**Use when:** the DPL names a Sphynx.
**Breed-specific food we carry:**
- Royal Canin Feline Breed Nutrition Sphynx Adult Cat Food (FCM06460): dry; life stage Adult

### DOG · Breed · Yorkshire Terrier

**Use when:** the DPL names a Yorkshire Terrier. Base profile size: Small.
**Breed-specific food we carry:**
- Royal Canin Breed Health Nutrition Yorkshire Terrier Adult Dog Food (FCM00265): dry; life stage Adult
- Royal Canin Breed Health Nutrition Yorkshire Terrier Loaf In Sauce Adult Dog Food (FCM05422): wet; life stage Adult
- Royal Canin Breed Health Nutrition Yorkshire Terrier Puppy Dog Food (FCM06487): dry; life stage Puppy

Breed size guide for common breeds we do not carry a breed formula for: toy and small (Maltese, Pomeranian, Bichon, Jack Russell, Boston Terrier, Corgi, Beagle is small to medium); medium (Border Collie, Cocker Spaniel, Australian Shepherd); large (Husky, Doberman, Great Dane is giant: use large-breed and "Giant" formulas).

## 11. Dog and cat situations


### DOG · Situation · New puppy starter kit

**Use when:** the DPL has just brought home a puppy or is getting ready for one. Combine with the puppy base profile for the dog's size.
**Keywords:** new puppy, first dog, puppy checklist, bringing puppy home, puppy essentials

**Basket items, in order:**

1. **Puppy food**
   - Category: Dog > Food; Dog > Food > Dry Food
   - Search: dog puppy food
   - Look for: match the breeder's or shelter's food first if the DPL knows it
   - In catalogue: flagged starter items: 102 → puppy dry food: 217
2. **Training treats**
   - Category: Dog > Treats; Dog > Treats > Training Treats
   - Search: dog training treats
   - Look for: small and soft
   - In catalogue: flagged starter items: 79 → training treats: 168
   - Ask the DPL: "Has training started?"
3. **Crate, pad and gate**
   - Category: Dog > Supplies > Crates, Pens & Gates > Crates & Pens; Dog > Supplies > Beds & Mats > Crate Mats & Pads; Dog > Supplies > Crates, Pens & Gates > Crate Mats & Accessories; Dog > Supplies > Crates, Pens & Gates > Doors & Gates; Dog > Supplies > Beds & Mats > Beds
   - Search: dog crate, pad and gate
   - Look for: crate for adult size, washable pad
   - In catalogue: flagged starter items: 31 → crates and pens: 11
   - Ask the DPL: "Where will the puppy sleep?"
4. **Collar, leash, harness and ID**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes; Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > ID Tags & Accessories
   - Search: dog collar, leash, harness and id
   - Look for: adjustable sizes
   - In catalogue: flagged starter items: 80 → ID tags: 128
   - Ask the DPL: "Does the puppy have ID on yet?"
5. **Potty training**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Diapers & Potty Pads; Dog > Supplies > Training & Behaviour > Potty Training Aids; Dog > Supplies > Clean Up & Potty Pads > Stain & Odour Removers
   - Search: dog potty training
   - Look for: pads, bells, stain remover
   - In catalogue: flagged starter items: 19 → potty pads and training aids: 31
   - Ask the DPL: "How is house training going?"
6. **Chew and plush toys**
   - Category: Dog > Supplies > Toys; Dog > Supplies > Toys > Chew Toys
   - Search: dog chew and plush toys
   - Look for: teething, plush
   - In catalogue: flagged starter items: 70 → chew toys: 87
   - Ask the DPL: "What is the puppy chewing?"
7. **Bowls**
   - Category: Dog > Supplies > Bowls & Feeding; Dog > Supplies > Bowls & Feeding > Bowls
   - Search: dog bowls
   - Look for: bowls, mats
   - In catalogue: flagged starter items: 44 → bowls: 68
   - Ask the DPL: "Does the puppy have its own bowls?"
8. **Grooming basics**
   - Category: Dog > Supplies > Grooming; Dog > Supplies > Grooming > Shampoos & Conditioners
   - Search: dog grooming basics
   - Look for: puppy shampoo, wipes, brush
   - In catalogue: flagged starter items: 19 → shampoos and conditioners: 51
   - Ask the DPL: "Has the puppy had a first bath?"
9. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - In catalogue: flagged starter items: 18 → poop bags: 29
   - Ask the DPL: "Do you have bags for walks?"

### CAT · Situation · New kitten starter kit

**Use when:** the DPL has just brought home a kitten. Combine with the kitten base profile.
**Keywords:** new kitten, first cat, kitten checklist, kitten essentials

**Basket items, in order:**

1. **Kitten food**
   - Category: Cat > Food & Treats > Dry Food; Cat > Food & Treats > Wet Food
   - Search: cat kitten food
   - Look for: match the current food first if the DPL knows it
   - In catalogue: flagged starter items: 57 → kitten wet food: 215
2. **Litter box, litter and scoop**
   - Category: Cat > Litter & Accessories > Litter Boxes; Cat > Litter & Accessories > Litter; Cat > Litter & Accessories > Litter Mats & Accessories; Cat > Litter & Accessories > Litter Waste Disposal
   - Search: cat litter box, litter and scoop
   - Look for: low-sided pan, unscented litter, mat
   - In catalogue: flagged starter items: 43 → litter boxes: 32
   - Ask the DPL: "Is the litter box set up?"
3. **Scratcher or tree**
   - Category: Cat > Supplies > Furniture & Scratchers > Scratchers & Posts; Cat > Supplies > Furniture & Scratchers > Trees & Condos
   - Search: cat scratcher or tree
   - Look for: posts, trees
   - In catalogue: flagged starter items: 29 → scratchers and posts: 37
   - Ask the DPL: "Does the kitten have somewhere to scratch?"
4. **Toys**
   - Category: Cat > Supplies > Toys; Cat > Supplies > Toys > Teasers & Wands
   - Search: cat toys
   - Look for: wands, interactive, plush
   - In catalogue: flagged starter items: 44 → teasers and wands: 38
   - Ask the DPL: "What does the kitten pounce on?"
5. **Bowls or fountain**
   - Category: Cat > Supplies > Bowls & Feeding > Bowls; Cat > Supplies > Bowls & Feeding > Feeders & Waterers
   - Search: cat bowls or fountain
   - Look for: shallow bowls, fountain
   - In catalogue: flagged starter items: 21 → bowls: 56
   - Ask the DPL: "Does the kitten have its own bowls?"
6. **Carrier**
   - Category: Cat > Supplies > Carriers & Travel Accessories; Dog > Supplies > Carriers & Travel Accessories > Carriers & Strollers
   - Search: cat carrier
   - Look for: carrier
   - In catalogue: flagged starter items: 14 → carriers: 47
   - Ask the DPL: "Do you have a carrier for the first vet visit?"
7. **Collar and ID**
   - Category: Cat > Supplies > Collars, Leashes & Harnesses > Collars; Cat > Supplies > Collars, Leashes & Harnesses > ID Tags & Accessories
   - Search: cat collar and id
   - Look for: breakaway collar, tag
   - In catalogue: flagged starter items: 19 → collars: 40
   - Ask the DPL: "Will the kitten wear a collar?"
8. **Bed**
   - Category: Cat > Supplies > Beds
   - Search: cat bed
   - Look for: soft bed
   - In catalogue: flagged starter items: 8 → beds: 28
   - Ask the DPL: "Where will the kitten sleep?"

### DOG · Situation · Heavy chewer

**Use when:** the dog destroys toys or is a power chewer.
**Keywords:** heavy chewer, power chewer, destroys toys, aggressive chewer

**Basket items, in order:**

1. **Tough and durable toys**
   - Category: Dog > Supplies > Toys > Tough & Durable Toys
   - Search: dog tough and durable toys
   - Look for: "Tough & Durable"; repeat only the page's wording, never "indestructible"
   - In catalogue: tough and durable toys: 269
   - Ask the DPL: "What has the dog destroyed so far?"
2. **Long-lasting natural chews**
   - Category: Dog > Treats > Bones & Chews
   - Search: dog long-lasting natural chews
   - Look for: bones, antlers, bully sticks, collagen
   - In catalogue: bones and chews: 311
   - Ask the DPL: "Does the dog get chews to work on?"
3. **Treat-dispensing toys**
   - Category: Dog > Supplies > Toys; Dog > Supplies > Toys > Interactive & Puzzle Toys
   - Search: dog treat-dispensing toys
   - Look for: treat dispensing
   - In catalogue: treat-dispensing toys: 91 → interactive and puzzle toys: 99
   - Ask the DPL: "Does the dog like to work for treats?"
4. **Rope and tug toys**
   - Category: Dog > Supplies > Toys > Rope & Tug Toys
   - Search: dog rope and tug toys
   - Look for: rope, tug
   - In catalogue: rope and tug toys: 125
   - Ask the DPL: "Does the dog play tug?"

**Guardrail:** supervise chewing; suggest a size up for strong chewers.

### DOG · Situation · Training

**Use when:** the DPL is training the dog: obedience, leash manners, recall.
**Keywords:** training, obedience, leash pulling, recall, puppy class

**Basket items, in order:**

1. **Training treats**
   - Category: Dog > Treats > Training Treats
   - Search: dog training treats
   - Look for: small, soft, low calorie
   - In catalogue: training treats: 168
   - Ask the DPL: "What rewards work best for the dog?"
2. **Leash and harness**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > Harnesses; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog leash and harness
   - Look for: front-clip harness, training leash, long line
   - In catalogue: front-clip harnesses: 31 → harnesses: 108 → leashes: 202
   - Ask the DPL: "Does the dog pull on leash?"
3. **Training tools**
   - Category: Dog > Supplies > Training & Behaviour
   - Search: dog training tools
   - Look for: clickers, bells, treat pouches
   - In catalogue: training and behaviour: 99
   - Ask the DPL: "Are you working on anything specific?"
4. **Puzzle toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys
   - Search: dog puzzle toys
   - Look for: puzzle toys
   - In catalogue: interactive and puzzle toys: 99
   - Ask the DPL: "What keeps the dog thinking between sessions?"

### DOG · Situation · Picky eater

**Use when:** the dog is fussy, bored of kibble, or leaves food.
**Keywords:** picky eater, fussy, won't eat, bored of food

**Basket items, in order:**

1. **Food toppers and broths**
   - Category: Dog > Food > Broths & Food Toppers
   - Search: dog food toppers and broths
   - Look for: toppers, broths, meal mixers
   - In catalogue: broths and food toppers: 81
   - Ask the DPL: "Have you tried a topper or broth on the food?"
2. **Wet food**
   - Category: Dog > Food > Wet Food
   - Search: dog wet food
   - Look for: wet food in a protein the dog likes
   - In catalogue: wet food: 424
   - Ask the DPL: "Does the dog get wet food mixed in?"
3. **Freeze-dried or raw food**
   - Category: Dog > Food > Raw Food; Dog > Food > Freeze Dried Food; Dog > Food > Dehydrated & Air Dried Food; Dog > Food > Gently Cooked Food
   - Search: dog freeze-dried or raw food
   - Look for: freeze-dried, raw, air-dried
   - In catalogue: raw, freeze-dried, air-dried and gently cooked foods: 227
   - Ask the DPL: "Has the dog tried freeze-dried or raw?"
4. **High-value treats**
   - Category: Dog > Treats > Freeze Dried & Dehydrated Treats
   - Search: dog high-value treats
   - Look for: freeze-dried meat treats
   - In catalogue: freeze-dried and dehydrated treats: 117
   - Ask the DPL: "Which proteins does the dog get excited about?"

**Guardrail:** a dog that suddenly stops eating should see a vet.

### DOG · Situation · Grooming and shedding

**Use when:** the DPL is grooming at home or dealing with shedding.
**Keywords:** grooming, shedding, bath, brushing, nails

**Basket items, in order:**

1. **Brushes and deshedding tools**
   - Category: Dog > Supplies > Grooming > Deshedding Solutions; Dog > Supplies > Grooming > Brushes & Combs
   - Search: dog brushes and deshedding tools
   - Look for: brush for the coat type
   - In catalogue: deshedding solutions: 17 → brushes and combs: 32
   - Ask the DPL: "How often does the dog get brushed?"
2. **Shampoo and conditioner**
   - Category: Dog > Supplies > Grooming > Shampoos & Conditioners
   - Search: dog shampoo and conditioner
   - Look for: by coat or skin need
   - In catalogue: shampoos and conditioners: 51
   - Ask the DPL: "What do you bathe the dog with?"
3. **Paw and nail care**
   - Category: Dog > Supplies > Grooming > Paw & Nail Care
   - Search: dog paw and nail care
   - Look for: clippers, grinders, paw balm
   - In catalogue: paw and nail care: 12
   - Ask the DPL: "Do you trim nails at home?"
4. **Wipes and deodorizers**
   - Category: Dog > Supplies > Grooming > Deodorizers & Wipes
   - Search: dog wipes and deodorizers
   - Look for: wipes, sprays
   - In catalogue: deodorizers and wipes: 31
   - Ask the DPL: "Anything for between baths?"
5. **Ear and eye care**
   - Category: Dog > Supplies > Health & Wellness > Eye & Ear Care; Dog > Supplies > Grooming > Eye & Ear Care
   - Search: dog ear and eye care
   - Look for: ear cleaner, eye wipes
   - In catalogue: eye and ear care: 19
   - Ask the DPL: "Do the ears get cleaned regularly?"

Mention Pet Valu grooming services only if the store offers them.

### DOG · Situation · Travel and car rides

**Use when:** road trips, car rides, or travelling with the dog.
**Keywords:** travel, road trip, car, vacation, cottage

**Basket items, in order:**

1. **Car accessories**
   - Category: Dog > Supplies > Carriers & Travel Accessories > Car Accessories
   - Search: dog car accessories
   - Look for: seat covers, restraints, barriers
   - In catalogue: car accessories: 46
   - Ask the DPL: "How does the dog ride in the car?"
2. **Travel bowl and water bottle**
   - Category: Dog > Supplies > Bowls & Feeding > Water Bottles & Travel Bowls
   - Search: dog travel bowl and water bottle
   - Look for: collapsible bowls
   - In catalogue: water bottles and travel bowls: 30
   - Ask the DPL: "Do you carry water for the dog?"
3. **Carrier or travel crate**
   - Category: Dog > Supplies > Carriers & Travel Accessories > Carriers & Strollers; Dog > Supplies > Crates, Pens & Gates > Crates & Pens
   - Search: dog carrier or travel crate
   - Look for: carrier sized for the dog
   - In catalogue: carriers and strollers: 17 → crates and pens: 11
   - Ask the DPL: "Does the dog travel in a carrier?"
4. **Calming and travel aids**
   - Category: Dog > Supplies > Carriers & Travel Accessories > Travel Aids; Dog > Supplies > Health & Wellness > Calming & Anxiety
   - Search: dog calming and travel aids
   - Look for: calming chews, sprays
   - In catalogue: travel aids: 20 → calming and anxiety: 23
   - Ask the DPL: "How does the dog handle the car?"
5. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - In catalogue: poop bags: 29
   - Ask the DPL: "Stocked up for the trip?"

### DOG · Situation · Winter

**Use when:** cold weather, snow, salted sidewalks.
**Keywords:** winter, cold, snow, salt, coat, boots

**Basket items, in order:**

1. **Coats and sweaters**
   - Category: Dog > Supplies > Clothing & Accessories > Coats & Jackets; Dog > Supplies > Clothing & Accessories > Sweaters & Hoodies
   - Search: dog coats and sweaters
   - Look for: coat sized by back length
   - In catalogue: winter-season coats and sweaters: 38 → coats, jackets, sweaters and hoodies: 89
   - Ask the DPL: "Does the dog get cold on walks?"
2. **Boots and socks**
   - Category: Dog > Supplies > Clothing & Accessories > Boots & Socks
   - Search: dog boots and socks
   - Look for: boots sized by paw width
   - In catalogue: boots and socks: 33
   - Ask the DPL: "Does the dog walk on salted sidewalks?"
3. **Paw care**
   - Category: Dog > Supplies > Grooming > Paw & Nail Care
   - Search: dog paw care
   - Look for: paw balm, wipes
   - In catalogue: paw and nail care: 12
   - Ask the DPL: "How are the paws after winter walks?"
4. **Indoor enrichment**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys
   - Search: dog indoor enrichment
   - Look for: puzzle toys, chews
   - In catalogue: interactive and puzzle toys: 99
   - Ask the DPL: "What keeps the dog busy on cold days?"

### DOG · Situation · Summer and water

**Use when:** hot weather, swimming, cottage, beach.
**Keywords:** summer, heat, hot, swimming, beach, cottage, cooling

**Basket items, in order:**

1. **Life jackets and rain gear**
   - Category: Dog > Supplies > Clothing & Accessories > Life Jackets & Raincoats
   - Search: dog life jackets and rain gear
   - Look for: life jacket sized by weight and girth
   - In catalogue: life jackets and raincoats: 40
   - Ask the DPL: "Will the dog be near water?"
2. **Cooling products**
   - Category: Dog > Supplies
   - Search: dog cooling products
   - Look for: "Cooling" mats, vests, bandanas
   - In catalogue: products with a cooling feature or name: 33
   - Ask the DPL: "How does the dog handle the heat?"
3. **Water toys**
   - Category: Dog > Supplies > Toys
   - Search: dog water toys
   - Look for: "Water Toy" feature, floating toys
   - In catalogue: toys with a water-toy feature: 105
   - Ask the DPL: "Does the dog like to swim or fetch in water?"
4. **Travel bowl and water bottle**
   - Category: Dog > Supplies > Bowls & Feeding > Water Bottles & Travel Bowls
   - Search: dog travel bowl and water bottle
   - Look for: collapsible bowls
   - In catalogue: water bottles and travel bowls: 30
   - Ask the DPL: "Do you carry water on walks?"
5. **Frozen treats**
   - Category: Dog > Treats > Frozen Treats
   - Search: dog frozen treats
   - Look for: frozen treats
   - In catalogue: frozen treats: 40
   - Ask the DPL: "Any cool treats for hot days?"
6. **Flea and tick protection**
   - Category: Dog > Supplies > Flea & Tick
   - Search: dog flea and tick protection
   - Look for: follow the label weight range only
   - In catalogue: dog flea and tick: 49
   - Ask the DPL: "Is the dog protected for flea and tick season?"

**Guardrail:** flea and tick products: label weight range only, no dosing advice.

### DOG · Situation · Flea and tick season

**Use when:** the DPL asks about flea and tick prevention.
**Keywords:** flea, tick, prevention, spot treatment

**Basket items, in order:**

1. **Spot treatments**
   - Category: Dog > Supplies > Flea & Tick > Spot Treatments; Dog > Supplies > Flea & Tick
   - Search: dog spot treatments
   - Look for: match the label weight range exactly
   - In catalogue: spot treatments: 30 → all dog flea and tick: 49
   - Ask the DPL: "What does the dog weigh? The label sets the right pack."
2. **Sprays and home treatments**
   - Category: Dog > Supplies > Flea & Tick > Repellents & Treatment Sprays; Dog > Supplies > Flea & Tick > Home & Yard Treatments
   - Search: dog sprays and home treatments
   - Look for: repellent sprays, home and yard
   - In catalogue: repellents, sprays and home treatments: 8
   - Ask the DPL: "Do you also need something for the home or yard?"
3. **Shampoo and comb**
   - Category: Dog > Supplies > Grooming > Shampoos & Conditioners; Dog > Supplies > Grooming > Brushes & Combs
   - Search: dog shampoo and comb
   - Look for: shampoo, flea comb
   - In catalogue: shampoos and conditioners: 51 → brushes and combs: 32
   - Ask the DPL: "Do you bathe the dog after hikes?"

**Guardrail:** use only the product's label weight range. Never use a dog product on a cat. Infestations or reactions: refer to a vet.

### DOG · Situation · Raw or fresh feeder

**Use when:** the DPL feeds raw, freeze-dried, or gently cooked food, or wants to start.
**Keywords:** raw, frozen raw, freeze-dried, fresh food, gently cooked, BARF

**Basket items, in order:**

1. **Raw food**
   - Category: Dog > Food > Raw Food
   - Search: dog raw food
   - Look for: frozen raw: complete dinners, pure proteins
   - In catalogue: raw food: 78
2. **Freeze-dried and air-dried food**
   - Category: Dog > Food > Freeze Dried Food; Dog > Food > Dehydrated & Air Dried Food
   - Search: dog freeze-dried and air-dried food
   - Look for: freeze-dried, air-dried, dehydrated
   - In catalogue: freeze-dried food: 97 → dehydrated and air-dried food: 41
   - Ask the DPL: "Would a shelf-stable option help for travel?"
3. **Gently cooked food**
   - Category: Dog > Food > Gently Cooked Food
   - Search: dog gently cooked food
   - Look for: gently cooked
   - In catalogue: gently cooked food: 11
   - Ask the DPL: "Has the DPL tried gently cooked?"
4. **Bones and chews**
   - Category: Dog > Treats > Bones & Chews
   - Search: dog bones and chews
   - Look for: raw bones, natural chews
   - In catalogue: bones and chews: 311
   - Ask the DPL: "Does the dog get raw bones or chews?"
5. **Toppers and broths**
   - Category: Dog > Food > Broths & Food Toppers
   - Search: dog toppers and broths
   - Look for: bone broth, goat's milk
   - In catalogue: broths and food toppers: 81
   - Ask the DPL: "Any toppers or bone broth?"

Safe handling: remind the ACE that raw food is kept frozen and handled like raw meat.

### DOG · Situation · Rescue or newly adopted adult

**Use when:** the DPL has just adopted an adult dog.
**Keywords:** rescue, adopted, shelter dog, new adult dog

**Basket items, in order:**

1. **Adult food**
   - Category: Dog > Food > Dry Food
   - Search: dog adult food
   - Look for: match the shelter's food first if known, then transition
   - In catalogue: adult dry food: 441
2. **Collar, leash and ID tag**
   - Category: Dog > Supplies > Collars, Leashes & Harnesses > ID Tags & Accessories; Dog > Supplies > Collars, Leashes & Harnesses > Collars; Dog > Supplies > Collars, Leashes & Harnesses > Leashes
   - Search: dog collar, leash and id tag
   - Look for: secure collar or harness, tag
   - In catalogue: ID tags: 128 → collars: 156 → leashes: 202
   - Ask the DPL: "Does the dog have an ID tag yet?"
3. **Bed and crate**
   - Category: Dog > Supplies > Beds & Mats > Beds; Dog > Supplies > Crates, Pens & Gates > Crates & Pens
   - Search: dog bed and crate
   - Look for: bed, crate
   - In catalogue: beds: 66 → crates and pens: 11
   - Ask the DPL: "Does the dog have a quiet spot of its own?"
4. **Calming aids**
   - Category: Dog > Supplies > Health & Wellness > Calming & Anxiety
   - Search: dog calming aids
   - Look for: category "Calming & Anxiety"
   - In catalogue: calming and anxiety: 23
   - Ask the DPL: "How is the dog settling in?"
5. **Enrichment toys**
   - Category: Dog > Supplies > Toys > Interactive & Puzzle Toys; Dog > Supplies > Toys > Chew Toys
   - Search: dog enrichment toys
   - Look for: puzzle, chew
   - In catalogue: interactive and puzzle toys: 99 → chew toys: 87
   - Ask the DPL: "What does the dog like to play with?"

### CAT · Situation · Multi-cat home

**Use when:** two or more cats, or adding a second cat.
**Keywords:** multi cat, two cats, second cat, new cat introduction

**Basket items, in order:**

1. **Multi-cat litter**
   - Category: Cat > Litter & Accessories > Litter
   - Search: multi-cat litter
   - Look for: "Multi Cat" litter
   - In catalogue: litter tagged multi cat: 18 → litter: 70
   - Ask the DPL: "How many litter boxes do you have? One per cat plus one is the usual guide."
2. **Extra litter box**
   - Category: Cat > Litter & Accessories > Litter Boxes
   - Search: cat extra litter box
   - Look for: extra box, large or hooded
   - In catalogue: litter boxes: 32
   - Ask the DPL: "Do the cats share a box?"
3. **Cat tree with several levels**
   - Category: Cat > Supplies > Furniture & Scratchers > Trees & Condos
   - Search: cat tree with several levels
   - Look for: trees and condos
   - In catalogue: trees and condos: 41
   - Ask the DPL: "Do the cats have their own spots up high?"
4. **Extra scratchers**
   - Category: Cat > Supplies > Furniture & Scratchers > Scratchers & Posts
   - Search: cat extra scratchers
   - Look for: posts, corrugate
   - In catalogue: scratchers and posts: 37
   - Ask the DPL: "Is there a scratcher in each main room?"
5. **Feeding stations**
   - Category: Cat > Supplies > Bowls & Feeding > Bowls; Cat > Supplies > Bowls & Feeding > Feeders & Waterers
   - Search: cat feeding stations
   - Look for: extra bowls, feeders, fountain
   - In catalogue: bowls: 56 → feeders and waterers: 28
   - Ask the DPL: "Do the cats eat in separate spots?"
6. **Calming aids**
   - Category: Cat > Supplies > Health & Wellness > Calming & Anxiety
   - Search: cat calming aids
   - Look for: diffusers, sprays
   - In catalogue: calming and anxiety: 10
   - Ask the DPL: "How are the cats getting along?"

### CAT · Situation · Scratching furniture

**Use when:** the cat is scratching the couch, carpet or furniture.
**Keywords:** scratching, couch, furniture, claws

**Basket items, in order:**

1. **Scratching posts**
   - Category: Cat > Supplies > Furniture & Scratchers > Scratchers & Posts
   - Search: cat scratching posts
   - Look for: tall, sturdy posts; corrugate scratchers
   - In catalogue: scratchers and posts: 37
   - Ask the DPL: "Where is the cat scratching most?"
2. **Cat tree**
   - Category: Cat > Supplies > Furniture & Scratchers > Trees & Condos
   - Search: cat tree
   - Look for: trees and condos
   - In catalogue: trees and condos: 41
   - Ask the DPL: "Does the cat like to scratch up high?"
3. **Catnip**
   - Category: Cat > Supplies > Toys > Catnip & Grass
   - Search: catnip
   - Look for: catnip, sprays
   - In catalogue: catnip and grass: 33
   - Ask the DPL: "Have you tried catnip on the scratcher?"
4. **Repellents and training aids**
   - Category: Cat > Supplies > Cleaning & Repellents
   - Search: cat repellents and training aids
   - Look for: deterrent sprays, tape
   - In catalogue: cleaning and repellents: 23
   - Ask the DPL: "Do you want to protect a specific spot?"

### CAT · Situation · Bored indoor cat

**Use when:** the cat is bored, restless or destructive indoors.
**Keywords:** bored cat, enrichment, destructive, restless, zoomies

**Basket items, in order:**

1. **Interactive toys**
   - Category: Cat > Supplies > Toys > Lasers & Interactive Toys
   - Search: cat interactive toys
   - Look for: lasers, electronic, interactive
   - In catalogue: lasers and interactive toys: 69
   - Ask the DPL: "When is the cat most active?"
2. **Wand toys**
   - Category: Cat > Supplies > Toys > Teasers & Wands
   - Search: cat wand toys
   - Look for: teasers, wands
   - In catalogue: teasers and wands: 38
   - Ask the DPL: "Do you play together daily?"
3. **Cat tree or perch**
   - Category: Cat > Supplies > Furniture & Scratchers > Trees & Condos
   - Search: cat tree or perch
   - Look for: trees, condos
   - In catalogue: trees and condos: 41
   - Ask the DPL: "Can the cat watch out a window?"
4. **Tunnels and kickers**
   - Category: Cat > Supplies > Toys > Tunnels; Cat > Supplies > Toys > Kickers
   - Search: cat tunnels and kickers
   - Look for: tunnels, kickers
   - In catalogue: tunnels: 10 → kickers: 19
   - Ask the DPL: "Does the cat like to hide and pounce?"
5. **Slow or puzzle feeder**
   - Category: Cat > Supplies > Bowls & Feeding > Slow Feeders
   - Search: cat slow or puzzle feeder
   - Look for: slow feeders
   - In catalogue: slow feeders: 20
   - Ask the DPL: "Would mealtime as a game help?"
6. **Catnip and cat grass**
   - Category: Cat > Supplies > Toys > Catnip & Grass
   - Search: catnip and cat grass
   - Look for: catnip, grass
   - In catalogue: catnip and grass: 33
   - Ask the DPL: "Does the cat respond to catnip?"

### CAT · Situation · Litter setup or odour

**Use when:** the DPL asks about litter, litter boxes, odour or tracking.
**Keywords:** litter, litter box, odour, smell, tracking

**Basket items, in order:**

1. **Litter**
   - Category: Cat > Litter & Accessories > Litter
   - Search: cat litter
   - Look for: clumping clay, natural, silica, lightweight, unscented
   - In catalogue: litter tagged odour control or multi cat: 21 → litter: 70
   - Ask the DPL: "What litter do you use now?"
2. **Litter box**
   - Category: Cat > Litter & Accessories > Litter Boxes
   - Search: cat litter box
   - Look for: pans, hooded, automatic
   - In catalogue: litter boxes: 32
   - Ask the DPL: "Is the box big enough for the cat to turn around?"
3. **Mats and accessories**
   - Category: Cat > Litter & Accessories > Litter Mats & Accessories
   - Search: cat mats and accessories
   - Look for: mats, liners, scoops, deodorizers
   - In catalogue: litter mats and accessories: 43
   - Ask the DPL: "Is litter getting tracked around?"
4. **Waste disposal**
   - Category: Cat > Litter & Accessories > Litter Waste Disposal
   - Search: cat waste disposal
   - Look for: disposal systems, refills
   - In catalogue: litter waste disposal: 14
   - Ask the DPL: "How do you dispose of used litter?"
5. **Stain and odour remover**
   - Category: Cat > Supplies > Cleaning & Repellents > Stain & Odour Removers
   - Search: cat stain and odour remover
   - Look for: enzyme cleaners
   - In catalogue: stain and odour removers: 13
   - Ask the DPL: "Any accidents outside the box?"

**Guardrail:** a cat that suddenly stops using the box should see a vet.

### CAT · Situation · Picky eater

**Use when:** the cat is fussy or bored of its food.
**Keywords:** picky cat, fussy, won't eat

**Basket items, in order:**

1. **Toppers, broths and lickable treats**
   - Category: Cat > Food & Treats > Broths & Food Toppers
   - Search: cat toppers, broths and lickable treats
   - Look for: broths, purées, toppers
   - In catalogue: broths and food toppers: 90
   - Ask the DPL: "Have you tried a topper or lickable treat on the food?"
2. **Wet food variety**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food variety
   - Look for: variety packs, different textures
   - In catalogue: variety packs: 39 → wet food: 602
   - Ask the DPL: "Does the cat prefer pâté or chunks?"
3. **Freeze-dried or raw food**
   - Category: Cat > Food & Treats > Raw Food; Cat > Food & Treats > Freeze Dried, Dehydrated & Air Dried Food
   - Search: cat freeze-dried or raw food
   - Look for: freeze-dried, raw
   - In catalogue: raw and freeze-dried food: 69
   - Ask the DPL: "Has the cat tried freeze-dried?"
4. **Freeze-dried treats**
   - Category: Cat > Food & Treats > Treats > Freeze Dried & Dehydrated Treats
   - Search: cat freeze-dried treats
   - Look for: single-protein treats
   - In catalogue: freeze-dried treats: 50
   - Ask the DPL: "Which proteins does the cat love?"

**Guardrail:** a cat that stops eating should see a vet promptly.

### CAT · Situation · Travel and vet visits

**Use when:** the DPL is travelling with the cat or preparing for a vet visit.
**Keywords:** travel, vet visit, carrier, moving

**Basket items, in order:**

1. **Carrier**
   - Category: Cat > Supplies > Carriers & Travel Accessories
   - Search: cat carrier
   - Look for: hard or soft carrier
   - In catalogue: carriers: 47
   - Ask the DPL: "Is the carrier big enough for the cat to turn around?"
2. **Calming aids**
   - Category: Cat > Supplies > Health & Wellness > Calming & Anxiety
   - Search: cat calming aids
   - Look for: sprays, treats
   - In catalogue: calming and anxiety: 10
   - Ask the DPL: "How does the cat handle the carrier?"
3. **Harness and leash**
   - Category: Cat > Supplies > Collars, Leashes & Harnesses > Leashes & Harnesses
   - Search: cat harness and leash
   - Look for: cat harness
   - In catalogue: leashes and harnesses: 29
   - Ask the DPL: "Will the cat need to come out of the carrier?"
4. **ID tag**
   - Category: Cat > Supplies > Collars, Leashes & Harnesses > ID Tags & Accessories
   - Search: cat id tag
   - Look for: tags
   - In catalogue: ID tags and accessories: 104
   - Ask the DPL: "Is the cat's ID up to date?"

### DOG and CAT · Situation · Gifts and occasions

**Use when:** birthday, holiday, Halloween, or a gift for a pet or pet lover.
**Keywords:** gift, birthday, holiday, Halloween, Christmas, stocking

**Basket items, in order:**

1. **Birthday treats and toys**
   - Category: 
   - Search: birthday treats and toys for dogs and cats
   - Look for: season "Birthday"
   - In catalogue: birthday items: 48
   - Ask the DPL: "Whose birthday is it?"
2. **Bakery treats**
   - Category: Dog > Treats > Bakery & Biscuits
   - Search: dog bakery treats
   - Look for: decorated biscuits, cakes, donuts
   - In catalogue: bakery and biscuits: 268
   - Ask the DPL: "Does the pet like a special treat?"
3. **Plush toys**
   - Category: Dog > Supplies > Toys > Plush Toys; Cat > Supplies > Toys > Plush Toys
   - Search: dog plush toys
   - Look for: plush
   - In catalogue: dog plush toys: 313 → cat plush toys: 107
   - Ask the DPL: "What kind of toys does the pet love?"
4. **Gifts for pet lovers**
   - Category: Dog > Supplies > Gifts; Cat > Supplies > Gifts
   - Search: dog gifts for pet lovers
   - Look for: mugs, frames
   - In catalogue: gifts: 28
   - Ask the DPL: "Is it for the pet or the pet parent?"
5. **Seasonal items**
   - Category: 
   - Search: seasonal items for dogs and cats
   - Look for: Halloween, Valentine's, Easter, winter, summer
   - In catalogue: Halloween items: 77 → Valentine's items: 17
   - Ask the DPL: "Is it for a holiday?"

Seasonal ranges change through the year: Summer (89), Winter (80), Fall (78), Halloween (77), Birthday (48), Spring (45), Valentines (17), Wedding (10), Pride (10), Easter (7), Spring/summer (3), St Patricks Day (1) products are flagged right now.

## 12. Small pet, bird, fish and reptile profiles

Food is species-specific: always confirm the species before recommending food. Supplies such as bedding, hideouts and bottles are usually shared across species; check the size on the page.


### SMALL PET · Rabbit

**Use when:** the DPL has a rabbit.
**Keywords:** rabbit, bunny

**Basket items, in order:**

1. **Rabbit food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet rabbit food
   - Look for: "Rabbit" in the product name; pellets or mix
   - In catalogue: food naming rabbit in the title: 25 → food tagged for rabbit: 27
2. **Hay**
   - Category: Small Pet > Food, Treats & Hay > Hay
   - Search: small pet hay
   - Look for: timothy for adults; alfalfa for young animals
   - In catalogue: hay: 29
   - Ask the DPL: "How do you serve hay? It should be available all day."
3. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming rabbit in the title: 9 → treats tagged for rabbit: 79
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
4. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for rabbit: 25 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
5. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for rabbit: 62 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
6. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for rabbit: 18 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
7. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for rabbit: 25 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
8. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for rabbit: 10 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

### SMALL PET · Guinea Pig

**Use when:** the DPL has a guinea pig.
**Keywords:** guinea pig, cavy

**Basket items, in order:**

1. **Guinea Pig food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet guinea pig food
   - Look for: "Guinea Pig" in the product name; pellets or mix
   - In catalogue: food naming guinea pig in the title: 17 → food tagged for guinea pig: 19
2. **Hay**
   - Category: Small Pet > Food, Treats & Hay > Hay
   - Search: small pet hay
   - Look for: timothy for adults; alfalfa for young animals
   - In catalogue: hay: 29
   - Ask the DPL: "How do you serve hay? It should be available all day."
3. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming guinea pig in the title: 5 → treats tagged for guinea pig: 77
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
4. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for guinea pig: 24 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
5. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for guinea pig: 68 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
6. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for guinea pig: 18 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
7. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for guinea pig: 25 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
8. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for guinea pig: 11 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

Guinea pigs need vitamin C in their diet: point to food made for guinea pigs.

### SMALL PET · Hamster

**Use when:** the DPL has a hamster.
**Keywords:** hamster, dwarf hamster, syrian

**Basket items, in order:**

1. **Hamster food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet hamster food
   - Look for: "Hamster" in the product name; pellets or mix
   - In catalogue: food naming hamster in the title: 11 → food tagged for hamster: 12
2. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming hamster in the title: 4 → treats tagged for hamster: 66
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
3. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for hamster: 23 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
4. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for hamster: 71 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
5. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for hamster: 19 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
6. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for hamster: 19 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
7. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for hamster: 10 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

### SMALL PET · Gerbil

**Use when:** the DPL has a gerbil.
**Keywords:** gerbil

**Basket items, in order:**

1. **Gerbil food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet gerbil food
   - Look for: "Gerbil" in the product name; pellets or mix
   - In catalogue: food naming gerbil in the title: 5 → food tagged for gerbil: 6
2. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming gerbil in the title: 0 → treats tagged for gerbil: 12
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
3. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for gerbil: 3 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
4. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for gerbil: 5 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
5. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for gerbil: 1 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
6. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for gerbil: 1 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
7. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for gerbil: 0 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

### SMALL PET · Rat / Mouse

**Use when:** the DPL has a rat / mouse.
**Keywords:** rat, mouse, mice

**Basket items, in order:**

1. **Rat / Mouse food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet rat / mouse food
   - Look for: "Rat / Mouse" in the product name; pellets or mix
   - In catalogue: food naming rat / mouse in the title: 9 → food tagged for rat / mouse: 10
2. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming rat / mouse in the title: 1 → treats tagged for rat / mouse: 61
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
3. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for rat / mouse: 22 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
4. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for rat / mouse: 70 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
5. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for rat / mouse: 17 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
6. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for rat / mouse: 18 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
7. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for rat / mouse: 8 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

### SMALL PET · Chinchilla

**Use when:** the DPL has a chinchilla.
**Keywords:** chinchilla

**Basket items, in order:**

1. **Chinchilla food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet chinchilla food
   - Look for: "Chinchilla" in the product name; pellets or mix
   - In catalogue: food naming chinchilla in the title: 5 → food tagged for chinchilla: 6
2. **Hay**
   - Category: Small Pet > Food, Treats & Hay > Hay
   - Search: small pet hay
   - Look for: timothy for adults; alfalfa for young animals
   - In catalogue: hay: 29
   - Ask the DPL: "How do you serve hay? It should be available all day."
3. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming chinchilla in the title: 2 → treats tagged for chinchilla: 71
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
4. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for chinchilla: 21 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
5. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for chinchilla: 57 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
6. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for chinchilla: 14 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
7. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for chinchilla: 23 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
8. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for chinchilla: 7 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

Chinchillas use a dust bath, not water baths.

### SMALL PET · Ferret

**Use when:** the DPL has a ferret.
**Keywords:** ferret

**Basket items, in order:**

1. **Ferret food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet ferret food
   - Look for: "Ferret" in the product name; pellets or mix
   - In catalogue: food naming ferret in the title: 4 → food tagged for ferret: 4
2. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming ferret in the title: 4 → treats tagged for ferret: 40
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
3. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for ferret: 24 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
4. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for ferret: 57 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
5. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for ferret: 15 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
6. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for ferret: 19 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
7. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for ferret: 8 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

Ferrets are carnivores: use ferret food, not rodent mixes.

### SMALL PET · Degu

**Use when:** the DPL has a degu.
**Keywords:** degu

**Basket items, in order:**

1. **Degu food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet degu food
   - Look for: "Degu" in the product name; pellets or mix
   - In catalogue: food naming degu in the title: 2 → food tagged for degu: 2
2. **Hay**
   - Category: Small Pet > Food, Treats & Hay > Hay
   - Search: small pet hay
   - Look for: timothy for adults; alfalfa for young animals
   - In catalogue: hay: 29
   - Ask the DPL: "How do you serve hay? It should be available all day."
3. **Treats and chews**
   - Category: Small Pet > Food, Treats & Hay > Treats
   - Search: small pet treats and chews
   - Look for: chews, treat sticks
   - In catalogue: treats naming degu in the title: 0 → treats tagged for degu: 4
   - Ask the DPL: "Does the pet have things to chew? It keeps teeth worn down."
4. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for degu: 0 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
5. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for degu: 1 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
6. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for degu: 0 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
7. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for degu: 1 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
8. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for degu: 0 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

We carry very little for degus: say so and offer the nearest shared small-pet supplies.

### SMALL PET · Hedgehog

**Use when:** the DPL has a hedgehog.
**Keywords:** hedgehog

**Basket items, in order:**

1. **Hedgehog food**
   - Category: Small Pet > Food, Treats & Hay > Food
   - Search: small pet hedgehog food
   - Look for: "Hedgehog" in the product name; pellets or mix
   - In catalogue: food naming hedgehog in the title: 1 → food tagged for hedgehog: 1
2. **Bedding and litter**
   - Category: Small Pet > Supplies > Bedding & Litter
   - Search: small pet bedding and litter
   - Look for: paper bedding, litter
   - In catalogue: bedding tagged for hedgehog: 0 → bedding and litter: 28
   - Ask the DPL: "What bedding do you use?"
3. **Hideouts and toys**
   - Category: Small Pet > Supplies > Hideouts, Toys & Accessories
   - Search: small pet hideouts and toys
   - Look for: hideouts, tunnels, toys, wheels where suitable
   - In catalogue: hideouts, toys and accessories tagged for hedgehog: 0 → hideouts, toys and accessories: 94
   - Ask the DPL: "Does the pet have a place to hide?"
4. **Bowls and water bottles**
   - Category: Small Pet > Supplies > Bowls & Water Bottles
   - Search: small pet bowls and water bottles
   - Look for: bottles, bowls, feeders
   - In catalogue: bowls and bottles tagged for hedgehog: 0 → bowls and water bottles: 22
   - Ask the DPL: "Is the water bottle working well?"
5. **Health and grooming**
   - Category: Small Pet > Supplies > Health & Grooming
   - Search: small pet health and grooming
   - Look for: supplements, shampoo, brushes
   - In catalogue: health and grooming tagged for hedgehog: 1 → health and grooming: 55
   - Ask the DPL: "Do you groom or trim nails at home?"
6. **Habitat (new pet only)**
   - Category: Small Pet > Supplies > Cages, Habitats & Hutches
   - Search: small pet habitat
   - Look for: cage or habitat sized for the species
   - In catalogue: habitats naming or tagged for hedgehog: 0 → cages, habitats and hutches: 23
   - Ask the DPL: "Do you have a habitat picked out yet?"

**Not carried for this pet:** treats and chews. Say so and skip.

We carry very little for hedgehogs: say so and offer the nearest shared small-pet supplies.

### BIRD · Budgie or parakeet

**Use when:** the DPL has a budgie or parakeet.
**Keywords:** budgie, parakeet, budgerigar

**Basket items, in order:**

1. **Budgie or parakeet food**
   - Category: Bird > Food & Treats > Parakeet & Budgie
   - Search: bird budgie or parakeet food
   - Look for: category "Parakeet & Budgie"; seed mix or pellets
   - In catalogue: food naming this bird in the title: 8 → all food in the Parakeet & Budgie category: 22
2. **Treats**
   - Category: Bird > Food & Treats > Treats
   - Search: bird treats
   - Look for: treat sticks, millet, fruit and nut mixes
   - In catalogue: treats tagged for this bird: 11 → bird treats: 32
   - Ask the DPL: "Does the bird get treats or millet?"
3. **Perches, swings and ladders**
   - Category: Bird > Supplies > Perches, Swings & Ladders
   - Search: bird perches, swings and ladders
   - Look for: varied widths and textures
   - In catalogue: perches tagged for this bird: 16 → perches, swings and ladders: 22
   - Ask the DPL: "When were the perches last changed?"
4. **Toys**
   - Category: Bird > Supplies > Toys
   - Search: bird toys
   - Look for: foraging, shredding, bells; sized for the bird
   - In catalogue: toys tagged for this bird: 38 → bird toys: 52
   - Ask the DPL: "What does the bird like to chew or shred?"
5. **Feeders, waterers and cage accessories**
   - Category: Bird > Supplies > Cages & Cage Accessories > Feeders & Waterers; Bird > Supplies > Cages & Cage Accessories > Cage Accessories
   - Search: bird feeders, waterers and cage accessories
   - Look for: dishes, feeders, baths, liners, covers
   - In catalogue: feeders and waterers: 28 → cage accessories: 5
   - Ask the DPL: "Are the food and water dishes easy to clean?"
6. **Health and wellness**
   - Category: Bird > Supplies > Health & Wellness
   - Search: bird health and wellness
   - Look for: cuttlebone, vitamins, mineral blocks
   - In catalogue: bird health and wellness: 13
   - Ask the DPL: "Does the bird get a cuttlebone or mineral block?"
7. **Cage (new bird only)**
   - Category: Bird > Supplies > Cages & Cage Accessories > Cages & Stands
   - Search: cage
   - Look for: cage with bar spacing suited to the bird
   - In catalogue: cages tagged for this bird: 11 → cages and stands: 11
   - Ask the DPL: "Do you have a cage picked out yet?"

Remind the ACE: birds are sensitive to fumes and aerosols. Make no health claims.

### BIRD · Canary or finch

**Use when:** the DPL has a canary or finch.
**Keywords:** canary, finch

**Basket items, in order:**

1. **Canary or finch food**
   - Category: Bird > Food & Treats > Canary & Finch
   - Search: bird canary or finch food
   - Look for: category "Canary & Finch"; seed mix or pellets
   - In catalogue: food naming this bird in the title: 5 → all food in the Canary & Finch category: 11
2. **Treats**
   - Category: Bird > Food & Treats > Treats
   - Search: bird treats
   - Look for: treat sticks, millet, fruit and nut mixes
   - In catalogue: treats tagged for this bird: 16 → bird treats: 32
   - Ask the DPL: "Does the bird get treats or millet?"
3. **Perches, swings and ladders**
   - Category: Bird > Supplies > Perches, Swings & Ladders
   - Search: bird perches, swings and ladders
   - Look for: varied widths and textures
   - In catalogue: perches tagged for this bird: 12 → perches, swings and ladders: 22
   - Ask the DPL: "When were the perches last changed?"
4. **Toys**
   - Category: Bird > Supplies > Toys
   - Search: bird toys
   - Look for: foraging, shredding, bells; sized for the bird
   - In catalogue: toys tagged for this bird: 25 → bird toys: 52
   - Ask the DPL: "What does the bird like to chew or shred?"
5. **Feeders, waterers and cage accessories**
   - Category: Bird > Supplies > Cages & Cage Accessories > Feeders & Waterers; Bird > Supplies > Cages & Cage Accessories > Cage Accessories
   - Search: bird feeders, waterers and cage accessories
   - Look for: dishes, feeders, baths, liners, covers
   - In catalogue: feeders and waterers: 28 → cage accessories: 5
   - Ask the DPL: "Are the food and water dishes easy to clean?"
6. **Health and wellness**
   - Category: Bird > Supplies > Health & Wellness
   - Search: bird health and wellness
   - Look for: cuttlebone, vitamins, mineral blocks
   - In catalogue: bird health and wellness: 13
   - Ask the DPL: "Does the bird get a cuttlebone or mineral block?"
7. **Cage (new bird only)**
   - Category: Bird > Supplies > Cages & Cage Accessories > Cages & Stands
   - Search: cage
   - Look for: cage with bar spacing suited to the bird
   - In catalogue: cages tagged for this bird: 9 → cages and stands: 11
   - Ask the DPL: "Do you have a cage picked out yet?"

Remind the ACE: birds are sensitive to fumes and aerosols. Make no health claims.

### BIRD · Cockatiel, conure or lovebird

**Use when:** the DPL has a cockatiel, conure or lovebird.
**Keywords:** cockatiel, conure, lovebird

**Basket items, in order:**

1. **Cockatiel, conure or lovebird food**
   - Category: Bird > Food & Treats > Cockatiel & Conure
   - Search: cockatiel, conure or lovebird food
   - Look for: category "Cockatiel & Conure"; seed mix or pellets
   - In catalogue: food naming this bird in the title: 11 → all food in the Cockatiel & Conure category: 19
2. **Treats**
   - Category: Bird > Food & Treats > Treats
   - Search: bird treats
   - Look for: treat sticks, millet, fruit and nut mixes
   - In catalogue: treats tagged for this bird: 9 → bird treats: 32
   - Ask the DPL: "Does the bird get treats or millet?"
3. **Perches, swings and ladders**
   - Category: Bird > Supplies > Perches, Swings & Ladders
   - Search: bird perches, swings and ladders
   - Look for: varied widths and textures
   - In catalogue: perches tagged for this bird: 11 → perches, swings and ladders: 22
   - Ask the DPL: "When were the perches last changed?"
4. **Toys**
   - Category: Bird > Supplies > Toys
   - Search: bird toys
   - Look for: foraging, shredding, bells; sized for the bird
   - In catalogue: toys tagged for this bird: 40 → bird toys: 52
   - Ask the DPL: "What does the bird like to chew or shred?"
5. **Feeders, waterers and cage accessories**
   - Category: Bird > Supplies > Cages & Cage Accessories > Feeders & Waterers; Bird > Supplies > Cages & Cage Accessories > Cage Accessories
   - Search: bird feeders, waterers and cage accessories
   - Look for: dishes, feeders, baths, liners, covers
   - In catalogue: feeders and waterers: 28 → cage accessories: 5
   - Ask the DPL: "Are the food and water dishes easy to clean?"
6. **Health and wellness**
   - Category: Bird > Supplies > Health & Wellness
   - Search: bird health and wellness
   - Look for: cuttlebone, vitamins, mineral blocks
   - In catalogue: bird health and wellness: 13
   - Ask the DPL: "Does the bird get a cuttlebone or mineral block?"
7. **Cage (new bird only)**
   - Category: Bird > Supplies > Cages & Cage Accessories > Cages & Stands
   - Search: cage
   - Look for: cage with bar spacing suited to the bird
   - In catalogue: cages tagged for this bird: 5 → cages and stands: 11
   - Ask the DPL: "Do you have a cage picked out yet?"

Remind the ACE: birds are sensitive to fumes and aerosols. Make no health claims.

### BIRD · Parrot or macaw

**Use when:** the DPL has a parrot or macaw.
**Keywords:** parrot, macaw, african grey, amazon, cockatoo

**Basket items, in order:**

1. **Parrot or macaw food**
   - Category: Bird > Food & Treats > Parrot & Macaw
   - Search: bird parrot or macaw food
   - Look for: category "Parrot & Macaw"; seed mix or pellets
   - In catalogue: food naming this bird in the title: 19 → all food in the Parrot & Macaw category: 25
2. **Treats**
   - Category: Bird > Food & Treats > Treats
   - Search: bird treats
   - Look for: treat sticks, millet, fruit and nut mixes
   - In catalogue: treats tagged for this bird: 8 → bird treats: 32
   - Ask the DPL: "Does the bird get treats or millet?"
3. **Perches, swings and ladders**
   - Category: Bird > Supplies > Perches, Swings & Ladders
   - Search: bird perches, swings and ladders
   - Look for: varied widths and textures
   - In catalogue: perches tagged for this bird: 3 → perches, swings and ladders: 22
   - Ask the DPL: "When were the perches last changed?"
4. **Toys**
   - Category: Bird > Supplies > Toys
   - Search: bird toys
   - Look for: foraging, shredding, bells; sized for the bird
   - In catalogue: toys tagged for this bird: 23 → bird toys: 52
   - Ask the DPL: "What does the bird like to chew or shred?"
5. **Feeders, waterers and cage accessories**
   - Category: Bird > Supplies > Cages & Cage Accessories > Feeders & Waterers; Bird > Supplies > Cages & Cage Accessories > Cage Accessories
   - Search: bird feeders, waterers and cage accessories
   - Look for: dishes, feeders, baths, liners, covers
   - In catalogue: feeders and waterers: 28 → cage accessories: 5
   - Ask the DPL: "Are the food and water dishes easy to clean?"
6. **Health and wellness**
   - Category: Bird > Supplies > Health & Wellness
   - Search: bird health and wellness
   - Look for: cuttlebone, vitamins, mineral blocks
   - In catalogue: bird health and wellness: 13
   - Ask the DPL: "Does the bird get a cuttlebone or mineral block?"
7. **Cage (new bird only)**
   - Category: Bird > Supplies > Cages & Cage Accessories > Cages & Stands
   - Search: cage
   - Look for: cage with bar spacing suited to the bird
   - In catalogue: cages tagged for this bird: 0 → cages and stands: 11
   - Ask the DPL: "Do you have a cage picked out yet?"

Remind the ACE: birds are sensitive to fumes and aerosols. Make no health claims.

### BIRD · Wild bird feeding

**Use when:** the DPL feeds backyard or wild birds.
**Keywords:** wild bird, backyard birds, bird feeder, hummingbird, suet

**Basket items, in order:**

1. **Wild bird food**
   - Category: Bird > Food & Treats > Wild Bird
   - Search: wild bird food
   - Look for: category "Wild Bird"; seed, suet, nectar
   - In catalogue: wild bird food: 16
2. **Feeders**
   - Category: Bird > Supplies > Cages & Cage Accessories > Feeders & Waterers
   - Search: bird feeders
   - Look for: seed feeders, hummingbird feeders
   - In catalogue: feeders and waterers naming wild or outdoor birds: 7 → feeders and waterers: 28
   - Ask the DPL: "Do you have a feeder up already?"

### FISH · Betta

**Use when:** the DPL has a betta.
**Keywords:** betta, fighting fish

**Basket items, in order:**

1. **Betta food**
   - Category: Fish > Food > Betta
   - Search: fish betta food
   - Look for: category "Betta"; flakes, pellets, wafers
   - In catalogue: food naming betta in the title: 10 → all food in the Betta category: 28
2. **Water conditioner**
   - Category: Fish > Supplies > Water Care > Water Conditioners
   - Search: fish water conditioner
   - Look for: dechlorinator, conditioner
   - In catalogue: water conditioners: 24
   - Ask the DPL: "Do you treat tap water before water changes?"
3. **Filter media**
   - Category: Fish > Supplies > Filters & Media > Filter Media; Fish > Supplies > Filters & Media > Filters
   - Search: fish filter media
   - Look for: cartridges matched to the filter model
   - In catalogue: filter media: 72 → filters: 19
   - Ask the DPL: "When was the filter cartridge last changed?"
4. **Heater and thermometer**
   - Category: Fish > Supplies > Heating & Lighting; Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish heater and thermometer
   - Look for: heater sized for the tank volume
   - In catalogue: heaters and thermometers: 8 → heating and lighting: 14
   - Ask the DPL: "Is the tank heated?"
5. **Water testing and balance**
   - Category: Fish > Supplies > Water Care > Water Balance; Fish > Supplies > Water Care > Water Treatment
   - Search: fish water testing and balance
   - Look for: test kits, pH and bacteria products
   - In catalogue: water balance and treatment: 20
   - Ask the DPL: "Do you test the water?"
6. **Cleaning tools**
   - Category: Fish > Supplies > Cleaning & Maintenance
   - Search: fish cleaning tools
   - Look for: gravel vacuums, algae scrapers
   - In catalogue: cleaning and maintenance: 10
   - Ask the DPL: "How do you clean the gravel?"
7. **Decor and plants**
   - Category: Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish decor and plants
   - Look for: plants, ornaments, gravel
   - In catalogue: decor tagged for betta: 117 → aquarium decor and accessories: 117
   - Ask the DPL: "Does the fish have places to hide?"
8. **Aquarium kit (new tank only)**
   - Category: Fish > Supplies > Aquariums, Kits & Tanks
   - Search: fish aquarium kit
   - Look for: kit with filter and light; betta kits for bettas
   - In catalogue: aquariums and kits naming or tagged for betta: 19 → aquariums, kits and tanks: 22
   - Ask the DPL: "What size tank are you thinking of?"

New tanks need to cycle before fish are added: suggest the DPL ask in store about set-up. Sick fish: products in Fish Care, with no treatment claims.

### FISH · Goldfish

**Use when:** the DPL has a goldfish.
**Keywords:** goldfish

**Basket items, in order:**

1. **Goldfish food**
   - Category: Fish > Food > Goldfish
   - Search: goldfish food
   - Look for: category "Goldfish"; flakes, pellets, wafers
   - In catalogue: food naming goldfish in the title: 13 → all food in the Goldfish category: 33
2. **Water conditioner**
   - Category: Fish > Supplies > Water Care > Water Conditioners
   - Search: fish water conditioner
   - Look for: dechlorinator, conditioner
   - In catalogue: water conditioners: 24
   - Ask the DPL: "Do you treat tap water before water changes?"
3. **Filter media**
   - Category: Fish > Supplies > Filters & Media > Filter Media; Fish > Supplies > Filters & Media > Filters
   - Search: fish filter media
   - Look for: cartridges matched to the filter model
   - In catalogue: filter media: 72 → filters: 19
   - Ask the DPL: "When was the filter cartridge last changed?"
4. **Water testing and balance**
   - Category: Fish > Supplies > Water Care > Water Balance; Fish > Supplies > Water Care > Water Treatment
   - Search: fish water testing and balance
   - Look for: test kits, pH and bacteria products
   - In catalogue: water balance and treatment: 20
   - Ask the DPL: "Do you test the water?"
5. **Cleaning tools**
   - Category: Fish > Supplies > Cleaning & Maintenance
   - Search: fish cleaning tools
   - Look for: gravel vacuums, algae scrapers
   - In catalogue: cleaning and maintenance: 10
   - Ask the DPL: "How do you clean the gravel?"
6. **Decor and plants**
   - Category: Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish decor and plants
   - Look for: plants, ornaments, gravel
   - In catalogue: decor tagged for goldfish: 95 → aquarium decor and accessories: 117
   - Ask the DPL: "Does the fish have places to hide?"
7. **Aquarium kit (new tank only)**
   - Category: Fish > Supplies > Aquariums, Kits & Tanks
   - Search: fish aquarium kit
   - Look for: kit with filter and light; betta kits for bettas
   - In catalogue: aquariums and kits naming or tagged for goldfish: 11 → aquariums, kits and tanks: 22
   - Ask the DPL: "What size tank are you thinking of?"

New tanks need to cycle before fish are added: suggest the DPL ask in store about set-up. Sick fish: products in Fish Care, with no treatment claims.

### FISH · Tropical community fish

**Use when:** the DPL has a tropical community fish.
**Keywords:** tropical fish, tetra, guppy, community tank

**Basket items, in order:**

1. **Tropical community fish food**
   - Category: Fish > Food > Tropical Fish
   - Search: tropical community fish food
   - Look for: category "Tropical Fish"; flakes, pellets, wafers
   - In catalogue: food naming tropical community fish in the title: 9 → all food in the Tropical Fish category: 28
2. **Water conditioner**
   - Category: Fish > Supplies > Water Care > Water Conditioners
   - Search: fish water conditioner
   - Look for: dechlorinator, conditioner
   - In catalogue: water conditioners: 24
   - Ask the DPL: "Do you treat tap water before water changes?"
3. **Filter media**
   - Category: Fish > Supplies > Filters & Media > Filter Media; Fish > Supplies > Filters & Media > Filters
   - Search: fish filter media
   - Look for: cartridges matched to the filter model
   - In catalogue: filter media: 72 → filters: 19
   - Ask the DPL: "When was the filter cartridge last changed?"
4. **Heater and thermometer**
   - Category: Fish > Supplies > Heating & Lighting; Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish heater and thermometer
   - Look for: heater sized for the tank volume
   - In catalogue: heaters and thermometers: 8 → heating and lighting: 14
   - Ask the DPL: "Is the tank heated?"
5. **Water testing and balance**
   - Category: Fish > Supplies > Water Care > Water Balance; Fish > Supplies > Water Care > Water Treatment
   - Search: fish water testing and balance
   - Look for: test kits, pH and bacteria products
   - In catalogue: water balance and treatment: 20
   - Ask the DPL: "Do you test the water?"
6. **Cleaning tools**
   - Category: Fish > Supplies > Cleaning & Maintenance
   - Search: fish cleaning tools
   - Look for: gravel vacuums, algae scrapers
   - In catalogue: cleaning and maintenance: 10
   - Ask the DPL: "How do you clean the gravel?"
7. **Decor and plants**
   - Category: Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish decor and plants
   - Look for: plants, ornaments, gravel
   - In catalogue: decor tagged for tropical community fish: 76 → aquarium decor and accessories: 117
   - Ask the DPL: "Does the fish have places to hide?"
8. **Aquarium kit (new tank only)**
   - Category: Fish > Supplies > Aquariums, Kits & Tanks
   - Search: fish aquarium kit
   - Look for: kit with filter and light; betta kits for bettas
   - In catalogue: aquariums and kits naming or tagged for tropical community fish: 7 → aquariums, kits and tanks: 22
   - Ask the DPL: "What size tank are you thinking of?"

New tanks need to cycle before fish are added: suggest the DPL ask in store about set-up. Sick fish: products in Fish Care, with no treatment claims.

### FISH · Cichlid

**Use when:** the DPL has a cichlid.
**Keywords:** cichlid

**Basket items, in order:**

1. **Cichlid food**
   - Category: Fish > Food > Cichlid
   - Search: fish cichlid food
   - Look for: category "Cichlid"; flakes, pellets, wafers
   - In catalogue: food naming cichlid in the title: 6 → all food in the Cichlid category: 25
2. **Water conditioner**
   - Category: Fish > Supplies > Water Care > Water Conditioners
   - Search: fish water conditioner
   - Look for: dechlorinator, conditioner
   - In catalogue: water conditioners: 24
   - Ask the DPL: "Do you treat tap water before water changes?"
3. **Filter media**
   - Category: Fish > Supplies > Filters & Media > Filter Media; Fish > Supplies > Filters & Media > Filters
   - Search: fish filter media
   - Look for: cartridges matched to the filter model
   - In catalogue: filter media: 72 → filters: 19
   - Ask the DPL: "When was the filter cartridge last changed?"
4. **Heater and thermometer**
   - Category: Fish > Supplies > Heating & Lighting; Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish heater and thermometer
   - Look for: heater sized for the tank volume
   - In catalogue: heaters and thermometers: 8 → heating and lighting: 14
   - Ask the DPL: "Is the tank heated?"
5. **Water testing and balance**
   - Category: Fish > Supplies > Water Care > Water Balance; Fish > Supplies > Water Care > Water Treatment
   - Search: fish water testing and balance
   - Look for: test kits, pH and bacteria products
   - In catalogue: water balance and treatment: 20
   - Ask the DPL: "Do you test the water?"
6. **Cleaning tools**
   - Category: Fish > Supplies > Cleaning & Maintenance
   - Search: fish cleaning tools
   - Look for: gravel vacuums, algae scrapers
   - In catalogue: cleaning and maintenance: 10
   - Ask the DPL: "How do you clean the gravel?"
7. **Decor and plants**
   - Category: Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish decor and plants
   - Look for: plants, ornaments, gravel
   - In catalogue: decor tagged for cichlid: 95 → aquarium decor and accessories: 117
   - Ask the DPL: "Does the fish have places to hide?"
8. **Aquarium kit (new tank only)**
   - Category: Fish > Supplies > Aquariums, Kits & Tanks
   - Search: fish aquarium kit
   - Look for: kit with filter and light; betta kits for bettas
   - In catalogue: aquariums and kits naming or tagged for cichlid: 12 → aquariums, kits and tanks: 22
   - Ask the DPL: "What size tank are you thinking of?"

New tanks need to cycle before fish are added: suggest the DPL ask in store about set-up. Sick fish: products in Fish Care, with no treatment claims.

### FISH · Bottom feeders

**Use when:** the DPL has a bottom feeders.
**Keywords:** pleco, catfish, bottom feeder, algae eater

**Basket items, in order:**

1. **Bottom feeders food**
   - Category: Fish > Food > Bottom Feeders
   - Search: fish bottom feeders food
   - Look for: category "Bottom Feeders"; flakes, pellets, wafers
   - In catalogue: food naming bottom feeders in the title: 3 → all food in the Bottom Feeders category: 25
2. **Water conditioner**
   - Category: Fish > Supplies > Water Care > Water Conditioners
   - Search: fish water conditioner
   - Look for: dechlorinator, conditioner
   - In catalogue: water conditioners: 24
   - Ask the DPL: "Do you treat tap water before water changes?"
3. **Filter media**
   - Category: Fish > Supplies > Filters & Media > Filter Media; Fish > Supplies > Filters & Media > Filters
   - Search: fish filter media
   - Look for: cartridges matched to the filter model
   - In catalogue: filter media: 72 → filters: 19
   - Ask the DPL: "When was the filter cartridge last changed?"
4. **Heater and thermometer**
   - Category: Fish > Supplies > Heating & Lighting; Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish heater and thermometer
   - Look for: heater sized for the tank volume
   - In catalogue: heaters and thermometers: 8 → heating and lighting: 14
   - Ask the DPL: "Is the tank heated?"
5. **Water testing and balance**
   - Category: Fish > Supplies > Water Care > Water Balance; Fish > Supplies > Water Care > Water Treatment
   - Search: fish water testing and balance
   - Look for: test kits, pH and bacteria products
   - In catalogue: water balance and treatment: 20
   - Ask the DPL: "Do you test the water?"
6. **Cleaning tools**
   - Category: Fish > Supplies > Cleaning & Maintenance
   - Search: fish cleaning tools
   - Look for: gravel vacuums, algae scrapers
   - In catalogue: cleaning and maintenance: 10
   - Ask the DPL: "How do you clean the gravel?"
7. **Decor and plants**
   - Category: Fish > Supplies > Aquarium Decor & Accessories
   - Search: fish decor and plants
   - Look for: plants, ornaments, gravel
   - In catalogue: decor tagged for bottom feeders: 86 → aquarium decor and accessories: 117
   - Ask the DPL: "Does the fish have places to hide?"
8. **Aquarium kit (new tank only)**
   - Category: Fish > Supplies > Aquariums, Kits & Tanks
   - Search: fish aquarium kit
   - Look for: kit with filter and light; betta kits for bettas
   - In catalogue: aquariums and kits naming or tagged for bottom feeders: 14 → aquariums, kits and tanks: 22
   - Ask the DPL: "What size tank are you thinking of?"

New tanks need to cycle before fish are added: suggest the DPL ask in store about set-up. Sick fish: products in Fish Care, with no treatment claims.

### FISH · Koi and pond fish

**Use when:** the DPL has a pond with koi or goldfish.
**Keywords:** koi, pond, pond fish

**Basket items, in order:**

1. **Koi and pond food**
   - Category: Fish > Food > Koi & Pond Fish
   - Search: fish koi and pond food
   - Look for: category "Koi & Pond Fish"
   - In catalogue: koi and pond food: 9
2. **Pond water care**
   - Category: Fish > Supplies > Water Care
   - Search: fish pond water care
   - Look for: pond conditioners and treatments
   - In catalogue: water care naming pond or koi: 5 → water care tagged for koi and pond: 11
   - Ask the DPL: "How is the water clarity?"

### REPTILE · Bearded dragon

**Use when:** the DPL has a bearded dragon.
**Keywords:** bearded dragon, beardie

**Basket items, in order:**

1. **Bearded dragon food**
   - Category: Reptile > Food > Bearded Dragon
   - Search: reptile bearded dragon food
   - Look for: category "Bearded Dragon"; pellets, canned, freeze-dried
   - In catalogue: food naming bearded dragon in the title: 5 → all food in the Bearded Dragon category: 24
2. **Calcium and vitamins**
   - Category: Reptile > Supplies > Health & Wellness
   - Search: reptile calcium and vitamins
   - Look for: category "Health & Wellness"
   - In catalogue: health and wellness tagged for bearded dragon: 8 → reptile health and wellness: 14
   - Ask the DPL: "Do you dust food with calcium?"
3. **Heating and lighting**
   - Category: Reptile > Supplies > Heating & Lighting
   - Search: reptile heating and lighting
   - Look for: UVB, basking bulbs, heat mats, fixtures
   - In catalogue: heating and lighting tagged for bearded dragon: 38 → heating and lighting: 50
   - Ask the DPL: "When was the bulb last changed?"
4. **Substrate and bedding**
   - Category: Reptile > Supplies > Substrate & Bedding
   - Search: reptile substrate and bedding
   - Look for: substrate suited to the species
   - In catalogue: substrate tagged for bearded dragon: 19 → substrate and bedding: 19
   - Ask the DPL: "What do you use on the floor of the habitat?"
5. **Hides and decor**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Decor
   - Search: reptile hides and decor
   - Look for: hides, plants, branches
   - In catalogue: decor tagged for bearded dragon: 16 → decor: 17
   - Ask the DPL: "Does the pet have a warm and a cool hide?"
6. **Thermometers and accessories**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Accessories
   - Search: reptile thermometers and accessories
   - Look for: thermometers, hygrometers, timers, misters, dishes
   - In catalogue: accessories tagged for bearded dragon: 26 → accessories: 28
   - Ask the DPL: "How do you track temperature and humidity?"
7. **Habitat or kit (new pet only)**
   - Category: Reptile > Supplies > Habitats & Kits
   - Search: reptile habitat or kit
   - Look for: terrarium or starter kit sized for the adult animal
   - In catalogue: habitats tagged for bearded dragon: 12 → habitats and kits: 15
   - Ask the DPL: "Do you have a habitat picked out yet?"

UVB bulbs lose output over time: suggest the DPL check the bulb's replacement guide.

### REPTILE · Gecko

**Use when:** the DPL has a gecko.
**Keywords:** gecko, leopard gecko, crested gecko

**Basket items, in order:**

1. **Gecko food**
   - Category: Reptile > Food > Gecko
   - Search: reptile gecko food
   - Look for: category "Gecko"; pellets, canned, freeze-dried
   - In catalogue: food naming gecko in the title: 4 → all food in the Gecko category: 22
2. **Calcium and vitamins**
   - Category: Reptile > Supplies > Health & Wellness
   - Search: reptile calcium and vitamins
   - Look for: category "Health & Wellness"
   - In catalogue: health and wellness tagged for gecko: 9 → reptile health and wellness: 14
   - Ask the DPL: "Do you dust food with calcium?"
3. **Heating and lighting**
   - Category: Reptile > Supplies > Heating & Lighting
   - Search: reptile heating and lighting
   - Look for: UVB, basking bulbs, heat mats, fixtures
   - In catalogue: heating and lighting tagged for gecko: 38 → heating and lighting: 50
   - Ask the DPL: "When was the bulb last changed?"
4. **Substrate and bedding**
   - Category: Reptile > Supplies > Substrate & Bedding
   - Search: reptile substrate and bedding
   - Look for: substrate suited to the species
   - In catalogue: substrate tagged for gecko: 19 → substrate and bedding: 19
   - Ask the DPL: "What do you use on the floor of the habitat?"
5. **Hides and decor**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Decor
   - Search: reptile hides and decor
   - Look for: hides, plants, branches
   - In catalogue: decor tagged for gecko: 17 → decor: 17
   - Ask the DPL: "Does the pet have a warm and a cool hide?"
6. **Thermometers and accessories**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Accessories
   - Search: reptile thermometers and accessories
   - Look for: thermometers, hygrometers, timers, misters, dishes
   - In catalogue: accessories tagged for gecko: 26 → accessories: 28
   - Ask the DPL: "How do you track temperature and humidity?"
7. **Habitat or kit (new pet only)**
   - Category: Reptile > Supplies > Habitats & Kits
   - Search: reptile habitat or kit
   - Look for: terrarium or starter kit sized for the adult animal
   - In catalogue: habitats tagged for gecko: 10 → habitats and kits: 15
   - Ask the DPL: "Do you have a habitat picked out yet?"

Leopard and crested geckos have different heat and humidity needs: confirm which gecko.

### REPTILE · Turtle

**Use when:** the DPL has a turtle.
**Keywords:** turtle, tortoise, red-eared slider

**Basket items, in order:**

1. **Turtle food**
   - Category: Reptile > Food > Turtle
   - Search: reptile turtle food
   - Look for: category "Turtle"; pellets, canned, freeze-dried
   - In catalogue: food naming turtle in the title: 5 → all food in the Turtle category: 25
2. **Calcium and vitamins**
   - Category: Reptile > Supplies > Health & Wellness
   - Search: reptile calcium and vitamins
   - Look for: category "Health & Wellness"
   - In catalogue: health and wellness tagged for turtle: 12 → reptile health and wellness: 14
   - Ask the DPL: "Do you dust food with calcium?"
3. **Heating and lighting**
   - Category: Reptile > Supplies > Heating & Lighting
   - Search: reptile heating and lighting
   - Look for: UVB, basking bulbs, heat mats, fixtures
   - In catalogue: heating and lighting tagged for turtle: 37 → heating and lighting: 50
   - Ask the DPL: "When was the bulb last changed?"
4. **Substrate and bedding**
   - Category: Reptile > Supplies > Substrate & Bedding
   - Search: reptile substrate and bedding
   - Look for: substrate suited to the species
   - In catalogue: substrate tagged for turtle: 18 → substrate and bedding: 19
   - Ask the DPL: "What do you use on the floor of the habitat?"
5. **Hides and decor**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Decor
   - Search: reptile hides and decor
   - Look for: hides, plants, branches
   - In catalogue: decor tagged for turtle: 14 → decor: 17
   - Ask the DPL: "Does the pet have a warm and a cool hide?"
6. **Thermometers and accessories**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Accessories
   - Search: reptile thermometers and accessories
   - Look for: thermometers, hygrometers, timers, misters, dishes
   - In catalogue: accessories tagged for turtle: 26 → accessories: 28
   - Ask the DPL: "How do you track temperature and humidity?"
7. **Habitat or kit (new pet only)**
   - Category: Reptile > Supplies > Habitats & Kits
   - Search: reptile habitat or kit
   - Look for: terrarium or starter kit sized for the adult animal
   - In catalogue: habitats tagged for turtle: 6 → habitats and kits: 15
   - Ask the DPL: "Do you have a habitat picked out yet?"

Aquatic turtles also need water care: see the fish water conditioner and filter categories.

### REPTILE · Frog

**Use when:** the DPL has a frog.
**Keywords:** frog, amphibian

**Basket items, in order:**

1. **Frog food**
   - Category: Reptile > Food > Frog
   - Search: reptile frog food
   - Look for: category "Frog"; pellets, canned, freeze-dried
   - In catalogue: food naming frog in the title: 1 → all food in the Frog category: 20
2. **Calcium and vitamins**
   - Category: Reptile > Supplies > Health & Wellness
   - Search: reptile calcium and vitamins
   - Look for: category "Health & Wellness"
   - In catalogue: health and wellness tagged for frog: 9 → reptile health and wellness: 14
   - Ask the DPL: "Do you dust food with calcium?"
3. **Heating and lighting**
   - Category: Reptile > Supplies > Heating & Lighting
   - Search: reptile heating and lighting
   - Look for: UVB, basking bulbs, heat mats, fixtures
   - In catalogue: heating and lighting tagged for frog: 37 → heating and lighting: 50
   - Ask the DPL: "When was the bulb last changed?"
4. **Substrate and bedding**
   - Category: Reptile > Supplies > Substrate & Bedding
   - Search: reptile substrate and bedding
   - Look for: substrate suited to the species
   - In catalogue: substrate tagged for frog: 18 → substrate and bedding: 19
   - Ask the DPL: "What do you use on the floor of the habitat?"
5. **Hides and decor**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Decor
   - Search: reptile hides and decor
   - Look for: hides, plants, branches
   - In catalogue: decor tagged for frog: 17 → decor: 17
   - Ask the DPL: "Does the pet have a warm and a cool hide?"
6. **Thermometers and accessories**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Accessories
   - Search: reptile thermometers and accessories
   - Look for: thermometers, hygrometers, timers, misters, dishes
   - In catalogue: accessories tagged for frog: 25 → accessories: 28
   - Ask the DPL: "How do you track temperature and humidity?"
7. **Habitat or kit (new pet only)**
   - Category: Reptile > Supplies > Habitats & Kits
   - Search: reptile habitat or kit
   - Look for: terrarium or starter kit sized for the adult animal
   - In catalogue: habitats tagged for frog: 10 → habitats and kits: 15
   - Ask the DPL: "Do you have a habitat picked out yet?"

### REPTILE · Hermit crab

**Use when:** the DPL has a hermit crab.
**Keywords:** hermit crab

**Basket items, in order:**

1. **Hermit crab food**
   - Category: Reptile > Food > Hermit Crab
   - Search: reptile hermit crab food
   - Look for: category "Hermit Crab"; pellets, canned, freeze-dried
   - In catalogue: food naming hermit crab in the title: 1 → all food in the Hermit Crab category: 12
2. **Calcium and vitamins**
   - Category: Reptile > Supplies > Health & Wellness
   - Search: reptile calcium and vitamins
   - Look for: category "Health & Wellness"
   - In catalogue: health and wellness tagged for hermit crab: 6 → reptile health and wellness: 14
   - Ask the DPL: "Do you dust food with calcium?"
3. **Heating and lighting**
   - Category: Reptile > Supplies > Heating & Lighting
   - Search: reptile heating and lighting
   - Look for: UVB, basking bulbs, heat mats, fixtures
   - In catalogue: heating and lighting tagged for hermit crab: 32 → heating and lighting: 50
   - Ask the DPL: "When was the bulb last changed?"
4. **Substrate and bedding**
   - Category: Reptile > Supplies > Substrate & Bedding
   - Search: reptile substrate and bedding
   - Look for: substrate suited to the species
   - In catalogue: substrate tagged for hermit crab: 17 → substrate and bedding: 19
   - Ask the DPL: "What do you use on the floor of the habitat?"
5. **Hides and decor**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Decor
   - Search: reptile hides and decor
   - Look for: hides, plants, branches
   - In catalogue: decor tagged for hermit crab: 14 → decor: 17
   - Ask the DPL: "Does the pet have a warm and a cool hide?"
6. **Thermometers and accessories**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Accessories
   - Search: reptile thermometers and accessories
   - Look for: thermometers, hygrometers, timers, misters, dishes
   - In catalogue: accessories tagged for hermit crab: 27 → accessories: 28
   - Ask the DPL: "How do you track temperature and humidity?"
7. **Habitat or kit (new pet only)**
   - Category: Reptile > Supplies > Habitats & Kits
   - Search: reptile habitat or kit
   - Look for: terrarium or starter kit sized for the adult animal
   - In catalogue: habitats tagged for hermit crab: 5 → habitats and kits: 15
   - Ask the DPL: "Do you have a habitat picked out yet?"

### REPTILE · Snake

**Use when:** the DPL has a snake.
**Keywords:** snake, ball python, corn snake

**Basket items, in order:**

1. **Heating and lighting**
   - Category: Reptile > Supplies > Heating & Lighting
   - Search: reptile heating and lighting
   - Look for: heat mats, bulbs, thermostats
   - In catalogue: heating and lighting tagged for snakes: 4 → heating and lighting: 50
   - Ask the DPL: "How do you heat the enclosure?"
2. **Substrate and bedding**
   - Category: Reptile > Supplies > Substrate & Bedding
   - Search: reptile substrate and bedding
   - Look for: aspen, bark, coconut
   - In catalogue: substrate tagged for snakes: 3 → substrate and bedding: 19
   - Ask the DPL: "What substrate do you use?"
3. **Hides and decor**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Decor
   - Search: reptile hides and decor
   - Look for: hides, branches
   - In catalogue: decor: 17
   - Ask the DPL: "Does the snake have a hide on each end?"
4. **Thermometers and accessories**
   - Category: Reptile > Supplies > Habitat Decor & Accessories > Accessories
   - Search: reptile thermometers and accessories
   - Look for: thermometers, hygrometers, water dishes
   - In catalogue: accessories: 28
   - Ask the DPL: "How do you track temperature and humidity?"
5. **Habitat or kit (new pet only)**
   - Category: Reptile > Supplies > Habitats & Kits
   - Search: reptile habitat or kit
   - Look for: secure, escape-proof terrarium
   - In catalogue: habitats tagged for snakes: 7 → habitats and kits: 15
   - Ask the DPL: "Do you have an enclosure yet?"

**We do not carry snake food.** Say so plainly and build the basket from supplies only.

## 13. Fallback profiles

Use these only when nothing more specific matches. Fallbacks use everyday, broadly suitable products with no special-diet or health labels, and end with one question that lets AVA tailor the basket next.


### FALLBACK · Dog (no age, size or need given)

**Use when:** a dog question with no details, such as "dog food" or "something for my dog".
**Keywords:** dog, dog food, generic dog

**Basket items, in order:**

1. **Adult or all-life-stages dry food**
   - Category: Dog > Food > Dry Food
   - Search: dog adult or all-life-stages dry food
   - Look for: no size label, no special-diet label
   - In catalogue: adult dry food, no size or special-diet label: 119 → all life stages dry food: 138
2. **Treats**
   - Category: Dog > Treats > Soft & Chewy Treats; Dog > Treats > Bakery & Biscuits
   - Search: dog treats
   - Look for: soft and chewy or biscuits
   - In catalogue: soft and chewy treats: 184 → bakery and biscuits: 268
   - Ask the DPL: "What treats does the dog like?"
3. **Chews**
   - Category: Dog > Treats > Dental Chews & Treats; Dog > Treats > Bones & Chews
   - Search: dog chews
   - Look for: dental chews, natural chews
   - In catalogue: dental chews and treats: 91 → bones and chews: 311
   - Ask the DPL: "Does the dog like a chew?"
4. **Toy**
   - Category: Dog > Supplies > Toys > Balls & Fetch Toys; Dog > Supplies > Toys > Plush Toys
   - Search: dog toy
   - Look for: fetch, tug, plush
   - In catalogue: balls and fetch toys: 76 → plush toys: 313
   - Ask the DPL: "How does the dog like to play?"
5. **Poop bags**
   - Category: Dog > Supplies > Clean Up & Potty Pads > Poop Bags & Scoopers
   - Search: dog poop bags
   - In catalogue: poop bags and scoopers: 29
   - Ask the DPL: "Running low on bags?"

**Then ask:** "How old is the dog, and roughly how big?" Use the answer to switch to a base profile in section 4.

### FALLBACK · Cat (no age or need given)

**Use when:** a cat question with no details, such as "cat food" or "stuff for my cat".
**Keywords:** cat, cat food, generic cat

**Basket items, in order:**

1. **Adult or all-life-stages dry food**
   - Category: Cat > Food & Treats > Dry Food
   - Search: cat adult or all-life-stages dry food
   - Look for: no special-diet label
   - In catalogue: adult dry food, no special-diet label: 63 → all life stages dry food: 49
2. **Wet food**
   - Category: Cat > Food & Treats > Wet Food
   - Search: cat wet food
   - Look for: adult wet food
   - In catalogue: adult wet food, no special-diet label: 329
   - Ask the DPL: "Does the cat get wet food too?"
3. **Litter**
   - Category: Cat > Litter & Accessories > Litter
   - Search: cat litter
   - Look for: clumping litter
   - In catalogue: litter: 70
   - Ask the DPL: "Running low on litter?"
4. **Treats**
   - Category: Cat > Food & Treats > Treats > Crunchy Treats; Cat > Food & Treats > Broths & Food Toppers
   - Search: cat treats
   - Look for: crunchy or lickable
   - In catalogue: crunchy treats: 34 → broths and food toppers: 90
   - Ask the DPL: "What treats does the cat like?"
5. **Toy**
   - Category: Cat > Supplies > Toys > Teasers & Wands; Cat > Supplies > Toys > Catnip & Grass
   - Search: cat toy
   - Look for: wands, catnip
   - In catalogue: teasers and wands: 38 → catnip and grass: 33
   - Ask the DPL: "How does the cat like to play?"

**Then ask:** "How old is the cat, and is it indoor or outdoor?" Use the answer to switch to a base profile in section 8.

### FALLBACK · Fish (type not given)

**Use when:** a fish question where the type of fish is unknown.
**Keywords:** fish, aquarium, tank

**Basket items, in order:**

1. **Water conditioner**
   - Category: Fish > Supplies > Water Care > Water Conditioners
   - Search: fish water conditioner
   - Look for: dechlorinator
   - In catalogue: water conditioners: 24
   - Ask the DPL: "Do you treat tap water before water changes?"
2. **Filter media**
   - Category: Fish > Supplies > Filters & Media > Filter Media
   - Search: fish filter media
   - Look for: matched to the filter model
   - In catalogue: filter media: 72
   - Ask the DPL: "When was the filter cartridge last changed?"
3. **Water testing**
   - Category: Fish > Supplies > Water Care > Water Balance; Fish > Supplies > Water Care > Water Treatment
   - Search: fish water testing
   - Look for: test kits
   - In catalogue: water balance and treatment: 20
   - Ask the DPL: "Do you test the water?"
4. **Cleaning tools**
   - Category: Fish > Supplies > Cleaning & Maintenance
   - Search: fish cleaning tools
   - Look for: gravel vacuums
   - In catalogue: cleaning and maintenance: 10
   - Ask the DPL: "How do you clean the gravel?"

**Ask first for food:** "Is it a betta, goldfish, tropical fish, cichlid or a bottom feeder?" Food depends on the answer; do not suggest food until it is known.

### FALLBACK · Small pet, bird or reptile (species not given)

**Use when:** the question names a small pet, bird or reptile but not the species.
**Do not build a basket yet.** Food, heating and habitat differ by species, and the wrong food is worse than none.
**Ask one question:**
- Small pet: "Which pet is it: rabbit, guinea pig, hamster, gerbil, rat or mouse, chinchilla or ferret?"
- Bird: "Which bird is it: budgie, canary or finch, cockatiel or conure, or a parrot?"
- Reptile: "Which reptile is it: bearded dragon, gecko, turtle, snake, frog or hermit crab?"
Then use that species' profile in section 12.

### FALLBACK · Pet type unknown

**Use when:** the question does not say which pet, such as "best treats" or "need a new bed".
**Ask one question:** "Is this for a dog, a cat, or another pet?"
**Exception:** if the item only suits one pet (litter and scratchers are for cats; poop bags and dental chews are for dogs; hay is for small pets), assume that pet and use its fallback.

### FALLBACK · Category has no products

**Use when:** a basket item returns nothing on petvalu.ca for the filters given.
- Loosen the filter in the order shown under "In catalogue" for that item.
- If it is still empty, say "We don't carry that for this pet" and skip the item. Never substitute a product made for a different species.
- Known gaps: no snake food; very little for degus and hedgehogs; few medium-breed labelled dog foods; no size-labelled cat food; few calming foods (calming products are supplements and aids, not food).
