# JSON Study

## Instructions

Read this document entirely. Follow any links and study their content. Readings
and activities are **required** unless otherwise indicated.

## JSON

JSON is a way to represent data. It's typically used to communicate data between
a back-end (*api*) and a front-end (*client*). JSON is a string with a very
specific format. JSON is formally defined [here](http://www.json.org/).

[Example JSON strings](http://json.org/example.html) are a great way to become
familiar with the format.

JSON is not a dictionary. JSON is not an object, nor is it an object literal.
JSON is only a string with a specific format.

JSON cannot have comments, since it is just a string. Putting comments in JSON,
or otherwise treating JSON as if it is a JavaScript object literal, is a common
source of hard-to-debug errors.

JSON cannot have methods, since it is a data exchange format. Since it only
represents data, it cannot have behavior. It cannnot have behavior because it is
not an object.

JSON only looks like an object. It is not an object.

## JSON Example

As it makes sense to you please write the following in JSON format:

-   Jason has many things...
-   A Cat named Mr.Kitty
-   Two roommates named Dave and Miller
-   A Love of the Red Sox, Patriots and Bruins
-   Has lived in two places recently: 123 Fake street, and 2 Muchinfo Road

```json
{"title: Jason has many things"
  "JasonPet": {
    "Species": "cat",
    "Name": "Mr. Kitty"
  }
  "JasonRoommates"{
    "Species": "Human",
    "Quantity": "Two",
    "Roommate1Name": "Dave",
    "Roommate2Name": "Miller",
  }
  "JasonOldAddresses"{
    "Address1": "123 Fake street",
    "Address2": "2 Muchinfo Road",
  }
}
```

I forgot, my roomate Dave has two goldfish, one named Bob (he's red) and the
other named Mr.MagicNibbles (yellow) and bites a bit. Please copy the JSON you
already wrote and include the information about Dave's fish./ Merge or only
answer? I don't have this clear.

ANSWER:

```json
{"title": "Dave also has many things",
  "DavePet": {
    "Species": "fish",
    "Kind": "goldfish",
    "Quantity": "two",
      "Fish1":{
        "Name1": "Bob",
        "Color": "Red",
        "Personality": "Normal",
      },
      "Fish2":{
        "Name2": "Mr. MagicNibbles",
        "Color": "Yellow",
        "Personality": "Aggressive",
      }
    }
  }

```

MERGED:

```json
{"title: Jason has many things"
  "JasonPet": {
    "Species": "cat",
    "Name": "Mr. Kitty"
  }
  "JasonRoommates"{
    "Species": "Human",
    "Quantity": "Two",
    "Roommate1Name": "Miller",
    "Roommate2Name": "Dave",{
        "DavePet": {
          "Species": "fish",
          "Kind": "goldfish",
          "Quantity": "two",
            "Fish1":{
              "Name1": "Bob",
              "Color": "Red",
              "Personality": "Normal",
            },
            "Fish2":{
              "Name2": "Mr. MagicNibbles",
              "Color": "Yellow",
              "Personality": "Aggressive",
            }
        }
      }
  }
  "JasonOldAddresses"{
    "Address1": "123 Fake street",
    "Address2": "2 Muchinfo Road",
  }
}
```

## JSON Methods

Using the JSON your wrote above, can you write a method on the JSON?

```json
No because JSON is only data presented in strings, so it cannot have behaviors/methods
attached to it.
```

## JSON Comments

Using the JSON your wrote above, can you write a comment in the JSON?

```json
No because JSON is already text or a string. Therefore, it cannot have comments.
```
