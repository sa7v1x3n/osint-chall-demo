# Challenge Solution: Operation Lens

**Challenge Name:** "Operation Lens"  
**Challenge Question:**  
An anonymous tip line drops a single photo without any caption, location, or metadata details. Find the landmark and city shown in the image.

---

## Step-by-Step Investigation Flow

### Step 1: Observe the Image
The learner examines `assets/exhibit-a.png` and observes:
1. A grand, historic square monument with four prominent minarets.
2. Distinctive Indo-Islamic/Persian arches and balconies.
3. Warm nighttime lighting.
4. An active urban setting around the monument.

### Step 2: Reverse Image Search
The learner uploads the image (`exhibit-a.png`) to visual search engines:
1. **Google Lens** (highly recommended for landmark recognition)
2. **Yandex Images**
3. **Bing Visual Search**

The visual search engine will identify the structure as the **Charminar** located in **Hyderabad, India**.

### Step 3: Google Search Confirmation
The learner searches Google to confirm details and get additional context:
1. Search query: `"Charminar Hyderabad night photography"`
2. Compare the night architectural details of Charminar to check if they match the photo in the case file.

### Step 4: Map Verification
The learner locates the site on Google Maps:
1. Search for: `"Charminar, Hyderabad, Telangana, India"`
2. Use Google Street View or Satellite View to compare the surrounding street layout and verify the structure matches.

---

## Final Evidence Board (Flags Checked)

The case file accepts the following answers:
1. **Image Location/Monument:** `charminar` or `flag{charminar}`
2. **City:** `hyderabad` or `flag{hyderabad}`
3. **Time of Day (Q2):** `night` or `nighttime`
4. **Photographer Metadata (Q3):** `unknown`, `not available`, or `no metadata` *(Exif data is stripped on PNG upload)*

---

## Visual Investigation Layout

```
      EXHIBIT-A.PNG (Night Photo)
                 ↓
      ZOOM: Four Arches & Minarets
                 ↓
      REVERSE IMAGE SEARCH (Google Lens)
                 ↓
      GOOGLE RESULT: Charminar, Hyderabad
                 ↓
      MAP VERIFY (Google Maps)
                 ↓
      FINAL ANSWER SUBMISSION (charminar / hyderabad)
```

---

## Course Outcomes
By completing this challenge, learners acquire the following skills:
1. **Visual Geolocation:** How to use visual search engines (Google Lens) to identify obscure landmarks.
2. **Feature Comparison:** How to isolate unique architectural features (arches, lights, minarets) to cross-reference candidates.
3. **Map Verification:** How to double-check search results on satellite and street maps.
4. **EXIF Forensic Awareness:** Understanding why web/social uploads strip metadata (OPSEC) and how to search for EXIF fallback data.
