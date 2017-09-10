# Trusting_Open_Food_Facts

***** Introduction *****
I've never used the Open Food Facts database before and have no bias either way. I thought that as it is an an open database it would be interesting to look into the data and see if there any potential issues. Edit: My original thought had been to look at how this database could be used for analysis, but I swiftly realised that this isn't its purpose. This is a reference database.

***** Questions that might be interesting *****

- What is the mix of creators and how might that affect the data?
- Are there a lot of modifications to the database and why would that happen?
- Do certain users make a lot of modifications?
- What type of data is commonly missing?
- Is there a bias for certain countries?
- What relEvance do the cities and stores data have?

***** Goal ******
Establish where the Open Food Facts database is most likely to have errors and why. The goal is not to prove any errors, merely highlight potential bias in the data. Verifying errors would mean checking hundreds of thousands of products (I don't fancy that.)

***** What do Open Food Facts say about this? *****

"The information and data is submited by the Open Food Facts contributors. The contributors also send pictures of the product, its labels, ingredients lists and nutrition facts table. When in doubt, visitors can thus check the accuracy by themselves, and if there is an error, they can correct it on the spot."
The model would hopefully encourage accuracy but it's possible that country levels differences, systemic errors or real bastards might cause issues with the data.

*********************************************************************************
*********************************************************************************

***************** THEIR DESCRIPTION OF THE DATABASE *****************************



** A food products database **

Open Food Facts is a free, open, collbarative database of food products from around the world, with ingredients, allergens, nutrition facts and all the tidbits of information we can find on product labels.

** Made by everyone **

Open Food Facts is a non-profit association of volunteers. 5000+ contributors like you have added 100 000+ products from 150 countries using our Android, iPhone or Windows Phone app or their camera to scan barcodes and upload pictures of products and their labels.

** For everyone **

Data about food is of public interest and has to be open. The complete database is published as open data and can be reused by anyone and for any use. Check-out the cool reuses or make your own!

** Dataset structure **

The dataset contains a single table, FoodFacts, in CSV form in FoodFacts.csv and in SQLite form in database.sqlite.

The columns in Open Food Facts are as follows:

code (text)
url (text)
creator (text)
created_t (text)
created_datetime (text)
last_modified_t (text)
last_modified_datetime (text)
product_name (text)
generic_name (text)
quantity (text)
packaging (text)
packaging_tags (text)
brands (text)
brands_tags (text)
categories (text)
categories_tags (text)
categories_en (text)
origins (text)
origins_tags (text)
manufacturing_places (text)
manufacturing_places_tags (text)
labels (text)
labels_tags (text)
labels_en (text)
emb_codes (text)
emb_codes_tags (text)
first_packaging_code_geo (text)
cities (text)
cities_tags (text)
purchase_places (text)
stores (text)
countries (text)
countries_tags (text)
countries_en (text)
ingredients_text (text)
allergens (text)
allergens_en (text)
traces (text)
traces_tags (text)
traces_en (text)
serving_size (text)
no_nutriments (numeric)
additives_n (numeric)
additives (text)
additives_tags (text)
additives_en (text)
ingredients_from_palm_oil_n (numeric)
ingredients_from_palm_oil (numeric)
ingredients_from_palm_oil_tags (text)
ingredients_that_may_be_from_palm_oil_n (numeric)
ingredients_that_may_be_from_palm_oil (numeric)
ingredients_that_may_be_from_palm_oil_tags (text)
nutrition_grade_uk (numeric)
nutrition_grade_fr (text)
pnns_groups_1 (text)
pnns_groups_2 (text)
states (text)
states_tags (text)
states_en (text)
main_category (text)
main_category_en (text)
image_url (text)
image_small_url (text)
energy_100g (numeric)
energy_from_fat_100g (numeric)
fat_100g (numeric)
saturated_fat_100g (numeric)
butyric_acid_100g (numeric)
caproic_acid_100g (numeric)
caprylic_acid_100g (numeric)
capric_acid_100g (numeric)
lauric_acid_100g (numeric)
myristic_acid_100g (numeric)
palmitic_acid_100g (numeric)
stearic_acid_100g (numeric)
arachidic_acid_100g (numeric)
behenic_acid_100g (numeric)
lignoceric_acid_100g (numeric)
cerotic_acid_100g (numeric)
montanic_acid_100g (numeric)
melissic_acid_100g (numeric)
monounsaturated_fat_100g (numeric)
polyunsaturated_fat_100g (numeric)
omega_3_fat_100g (numeric)
alpha_linolenic_acid_100g (numeric)
eicosapentaenoic_acid_100g (numeric)
docosahexaenoic_acid_100g (numeric)
omega_6_fat_100g (numeric)
linoleic_acid_100g (numeric)
arachidonic_acid_100g (numeric)
gamma_linolenic_acid_100g (numeric)
dihomo_gamma_linolenic_acid_100g (numeric)
omega_9_fat_100g (numeric)
oleic_acid_100g (numeric)
elaidic_acid_100g (numeric)
gondoic_acid_100g (numeric)
mead_acid_100g (numeric)
erucic_acid_100g (numeric)
nervonic_acid_100g (numeric)
trans_fat_100g (numeric)
cholesterol_100g (numeric)
carbohydrates_100g (numeric)
sugars_100g (numeric)
sucrose_100g (numeric)
glucose_100g (numeric)
fructose_100g (numeric)
lactose_100g (numeric)
maltose_100g (numeric)
maltodextrins_100g (numeric)
starch_100g (numeric)
polyols_100g (numeric)
fiber_100g (numeric)
proteins_100g (numeric)
casein_100g (numeric)
serum_proteins_100g (numeric)
nucleotides_100g (numeric)
salt_100g (numeric)
sodium_100g (numeric)
alcohol_100g (numeric)
vitamin_a_100g (numeric)
beta_carotene_100g (numeric)
vitamin_d_100g (numeric)
vitamin_e_100g (numeric)
vitamin_k_100g (numeric)
vitamin_c_100g (numeric)
vitamin_b1_100g (numeric)
vitamin_b2_100g (numeric)
vitamin_pp_100g (numeric)
vitamin_b6_100g (numeric)
vitamin_b9_100g (numeric)
vitamin_b12_100g (numeric)
biotin_100g (numeric)
pantothenic_acid_100g (numeric)
silica_100g (numeric)
bicarbonate_100g (numeric)
potassium_100g (numeric)
chloride_100g (numeric)
calcium_100g (numeric)
phosphorus_100g (numeric)
iron_100g (numeric)
magnesium_100g (numeric)
zinc_100g (numeric)
copper_100g (numeric)
manganese_100g (numeric)
fluoride_100g (numeric)
selenium_100g (numeric)
chromium_100g (numeric)
molybdenum_100g (numeric)
iodine_100g (numeric)
caffeine_100g (numeric)
taurine_100g (numeric)
ph_100g (numeric)
fruits_vegetables_nuts_100g (numeric)
collagen_meat_protein_ratio_100g (numeric)
cocoa_100g (numeric)
chlorophyl_100g (numeric)
carbon_footprint_100g (numeric)
nutrition_score_fr_100g (numeric)
nutrition_score_uk_100g (numeric)
