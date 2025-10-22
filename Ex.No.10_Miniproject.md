# Ex.No: 10  Implementation of 2D/3D game in unity
### DATE:    22 / 10 / 2025                                                                        
### REGISTER NUMBER : 212223240160
### AIM: 
To develop a 3D platformer game in Unity using C# and to implement artificial intelligence using Unity ML-Agents Toolkit.

### DESCRIPTION:
This project is a 2D platformer game where the player can move and jump across platforms to collect coins scattered throughout the level. The goal is to gather as many coins as possible while navigating obstacles and reaching the end of the level.

### Algorithm:

1. Open Unity and create a 2D project.

2. Design the levelFESTIVE300 using 2D primitives and assets.
      
3. Implement Player Movement using Rigidbody2D and a C# script.
      
4. Create collectible coins as game objects with colliders.

5. Add obstacles or enemies if needed (optional).

6. Set up UI elements to display score and game status.

7. Test the game thoroughly, fixing bugs and polishing mechanics.
 
### Program:

##### Player.cs
```csharp
using UnityEngine;
using UnityEngine.SocialPlatforms.Impl;

public class Playe : MonoBehaviour
{/*
    public float speed, jumpforce;
    private Rigidbody2D rb;
    public Score cc;

    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        rb = GetComponent<Rigidbody2D>();
    }

    // Update is called once per frame
    void Update()
    {
        float moveinp =Input.GetAxisRaw("Horizontal");
        transform.position += new Vector3(moveinp, 0, 0) * speed * Time.deltaTime;
        if(Input.GetKeyDown(KeyCode.Escape)&& Mathf.Abs(rb.Velocity.y)<0.001f)
        {
            rb.AddForce(new Vector2(0, jumpforce), ForceMode2D.Impulse);
        }
    }
    private void OnTriggerEnter2D(Collider2D collision)
    {
        if (other.CompareTag("Destroy"))
        {
            cc.coincount++;
            Destroy(other.gameObject);
        }
    }*/
}

```
##### Score.cs
```

using UnityEngine;
using UnityEngine.UI;

public class Score : MonoBehaviour
{/*
    public int points = 0;          
    public Text pointsText;         
    // Call this method to add points when a coin is collected
    public void AddPoints(int amount)
    {
        points += amount;
        UpdateScoreText();
    }

    // Update the UI text to show the current score
    void UpdateScoreText()
    {
        if (pointsText != null)
        {
            pointsText.text = "Points: " + points.ToString();
        }
    }

    // Optional: Initialize score display at start
    void Start()
    {
        UpdateScoreText();
    }

}*/



```

### Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e6383dd9-4eba-4856-9ad8-8d5462c0e0de" />

### Result:
Thus, the 2D coin collecting game was successfully developed using Unity, featuring smooth player movement and coin collection mechanics to create an engaging gameplay experience.
