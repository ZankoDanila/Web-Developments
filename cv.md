# DANILA ZANKO
SOFTWARE DEVELOPER

![Danila Zanko Photo](https://github.com/ZankoDanila.png) 

## Contacts
* Phone: +375 25 750 8514
* Email: zanko.danila@gmail.com
* Telegram: [Telegram Profile](https://t.me/your_username)
* Location: Mogilev, Belarus

---

## SUMMARY
Results-oriented developer with a passion for Game Development and Mobile Solutions. Winner of the BrSTU Startup Contest.

* Participant of "100 Ideas for Belarus" (City Stage).
* First place in BrSTU startup contest (Welding equipment accounting app).
* Experience in C# and Unreal Engine 5 (C++/Blueprints).

---

## SKILLS
* Languages: C#, Kotlin, Python, C++, HTML5
* Engines: Unreal Engine 5, Unity
* Tools: Git, GitHub, VS Code

---

## CODE EXAMPLE (C#)

`csharp
// Simplified Battle Logic Fragment
static bool Battle(bool victory, Enemy enemy, Player player)
{
    int FastAttackEnergy = 2 + EquippedWeapon.weight;

    if (player.energy >= FastAttackEnergy)
    {
        enemy.health -= player.damage;
        player.energy -= FastAttackEnergy;
        return true;
    }
    return false;
}
