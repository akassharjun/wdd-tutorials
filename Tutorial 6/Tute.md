# Tute 6

## Question 1

```xml
<name>Oyster Soup</name>
<author>Jamie Oliver</author>
<ingredients>
  <list>
    <item ingredient=optional>1 stalk of celery</item>
    <item>1 onion</item>
    <item>2 tablespoons of butter</item>
    <item>2 cups of oysters and their liquor</item>
    <item>2 cups of milk</item>
  </list>
</ingredients>
<process>
  <p>Begin by sauteing the celery and onions in butter until
    soft.
    Add oysters, oyster liquor, and cream. Heat until the oysters
    float.
    Serve in warm bowls.</p>
   <p><i>Yummy!</i></p>
</process>
```
| Questions  | Answers |
| ------------- | ------------- |
|  Check for one root element.  | There is none  |
|  Check for properly opened and closed element tags.  | Item tag hasn't been closed.  |
|  Check for case sensitive element naming.  | One paragraph tag has been capitalized.  |
|  Check for properly nested elements. | One Italics tag hasn't been properly closed.  |
|  Check for quoted attribute values.   | idk  |

### Corrected XML

```xml
<?xml version="1.0" encoding="UTF-8"?>

<recipe>
  <name>Oyster Soup</name>
  <author>Jamie Oliver</author>
  <ingredients>
    <list>
      <item ingredient=optional>1 stalk of celery
      <item>1 onion
      <item>2 tablespoons of butter
      <item>2 cups of oysters and their liquor
      <item>2 cups of milk
    </list>
  </ingredients>
  <process>
    <p>Begin by sauteing the celery and onions in butter until
      soft.
      Add oysters, oyster liquor, and cream. Heat until the oysters
      float.
      Serve in warm bowls.</p>
    <p><i>Yummy!</i></p>
  </process>
</recipe>        
```
