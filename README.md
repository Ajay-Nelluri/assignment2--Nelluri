# Ajay Kumar Nelluri

## Hyderabad

Hyderabad is the capital of southern India's Telangana state. A major center for the **technology industry**, it's home to many upscale **restaurants** and shops.

---

# Ajay's Favourite place directions

###### Directions from Maryville to Hyderbad
1. To travel from Maryville need to take cab to KansasCity (MCI) Airport
2. From KansasCity(MCI) take flight and land in Chicago Internation Airpot (ORD)
3. From Chicago(ORD) travel in an international filght to Hyderabad (HYD) India.

## List  of items to brought to favourite place

1. Vehicle- To  travel all the locations in Hyderabad
2. Gadgets/costumes - Like costumes and  party speakers
3. Food 
   - fruits
   - salads
   - Meat and veggies
4. Money for expenses 

** [Bio](AboutMe.md)**

---

# Table for Food Items

The below table shows the must try food and drinks in Hyderabad including the cost for them.

| Food/ Drink | Location | Cost per Item in Rupees|
| :---:       | :-:      | :-:                |
| Biryani | Secunderabad | 280 |
| Kaju Sweet | Jubileehills | 1200 |
| Chat | Koti | 50 |
| Breakfast | Charminar | 90 |


---

# Quotes
> All we have to decide is what to do with the time that is given us.
>
> It matters not what someone is born, but what they grow to be
>
*J.R.R. Tolkein*

---

# Algorithms- String Hashing
>  String hashing is the way to convert a string into an integer known as a hash of that string. An ideal hashing is the one in which there are minimum chances of collision (i.e 2 different strings having the same hash).

```
long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}

```
[Code Source](https://cp-algorithms.com/string/string-hashing.html)












