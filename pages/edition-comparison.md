---
layout: page
title:  Game Editions Comparison and Notes
permalink: /editions
description: "A detailed comparison of the various editions available when purchasing Rainbow Six: Siege."
image: /assets/images/covers/standard.jpg
---

<style>
    table{
        min-width: 800px;
    }
    .sticky-header{
        position: sticky;
        top: 0;
    }
    .sticky-header th{
        background-color: #0e0f12;
    }
    img.edition-cover{
        width: 96px;
        max-width: 75%;
    }
    .none{
        color: #888;
        text-align: center;
    }
    .locked{
        color: #fc3;
        text-align: center;
    }
    .included{
        color: #3c3;
        text-align: center;
    }
    .locked small, .included small{
        color: #fff;
    }

    .table-toggleable-section{
        display: none;
    }
    .table-toggleable-section-expanded{
        display: table-row-group;
    }
    .table-toggle{
        text-align: center;
    }
    .table-toggle::after{
        content: '>';
        padding-left: 0.5em;
        display: inline-block;
        transform: translateY(-0.25em) translateX(0.25em) rotate(90deg);
        transition: 0.25s transform;
    }
    .table-toggle-expanded::after{
        transform: translateY(0.25em) translateX(0.25em) rotate(-90deg);
    }
</style>
<script>
    function toggleClass(element, name){
        if(element.classList.contains(name)){
            element.classList.remove(name);
        }
        else{
            element.classList.add(name);
        }
    }

    function toggleTableSection(evt, id){
        evt.preventDefault();

        var tbody = document.getElementById(id);
        var toggle = evt.target.parentElement;
        if(tbody.classList.contains("table-toggleable-section")){
            toggleClass(tbody, "table-toggleable-section-expanded");
            toggleClass(toggle, "table-toggle-expanded");
        }

        return false;
    }
</script>

The following is a detailed comparison of the various editions available when purchasing Rainbow Six: Siege. 

Rainbow Six: Siege allows unlocking all gameplay content including maps and operators simply through in-game progression. All maps and weapon attachments are instantly unlocked for all players out of the box. 

Additional information and context are provided after the table below. 
<div class="overflow-container">
    <table>
        <thead class="sticky-header">
            <tr>
                <th>Feature</th>
                <th>
                    <img src="/assets/images/covers/starter.jpg" class="edition-cover" alt="Starter edition cover">
                    <br>Starter Edition
                </th>
                <th>
                    <img src="/assets/images/covers/standard.jpg" class="edition-cover" alt="Standard edition cover">
                    <br>Standard Edition
                </th>
                <th>
                    <img src="/assets/images/covers/advanced.jpg" class="edition-cover" alt="Advanced edition cover">
                    <br>Advanced Edition
                </th>
                <th>
                    <img src="/assets/images/covers/gold.jpg" class="edition-cover" alt="Gold edition cover">
                    <br>Gold Edition (Year 3)
                </th>
                <th>
                    <img src="/assets/images/covers/complete.jpg" class="edition-cover" alt="Complete edition cover">
                    <br>Complete Edition
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>Summary</th>
                <td> <!--Starter Edition-->
                    A low-priced entry point to Siege, in exchange for more time needed to unlock operators.
                </td>
                <td> <!--Standard Edition-->
                    The normal base edition of the game.
                </td>
                <td> <!--Advanced Edition-->
                    Includes the Standard Edition, plus 600 R6 Credits and 10 Outbreak Packs.
                </td>
                <td> <!--Gold Edition (Year 3)-->
                    Includes the Advanced Edition, plus the Year 3 Pass.
                </td>
                <td> <!--Complete Edition-->
                    Includes the Gold Edition, plus all Year 1 and Year 2 operators unlocked.
                </td>
            </tr>
            <tr>
                <th>Maps</th>
                <td class="included">Included</td>
                <td class="included">Included</td>
                <td class="included">Included</td>
                <td class="included">Included</td>
                <td class="included">Included</td>
            </tr>
            <tr>
                <th rowspan="5">Operators*</th>
                <td> <!--Starter Edition-->
                    <div class="table-emphasis"><em>6</em> unlocked</div>
                </td>
                <td> <!--Standard Edition-->
                    <div class="table-emphasis"><em>20</em> unlocked</div>
                </td>
                <td> <!--Advanced Edition-->
                    <div class="table-emphasis"><em>20</em> unlocked</div>
                </td>
                <td> <!--Gold Edition (Year 3)-->
                    <div class="table-emphasis"><em>28</em> unlocked</div>
                </td>
                <td> <!--Complete Edition-->
                    <div class="table-emphasis"><em>44</em> unlocked</div>
                </td>
            </tr>
            <tr>
                <td class="locked">6 randomly selected Original operators*</td>
                <td class="included">20 Original operators</td>
                <td class="included">20 Original operators</td>
                <td class="included">20 Original operators</td>
                <td class="included">20 Original operators</td>
            </tr>
            <tr>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="included">8 Year 1 operators</td>
            </tr>
            <tr>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="included">8 Year 2 operators</td>
            </tr>
            <tr>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="none">Not included</td>
                <td class="included">8 Year 3 operators</td>
                <td class="included">8 Year 3 operators</td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <td colspan="6" class="table-toggle">* <a href="#" onclick="toggleTableSection(event, 'table-operators')">Additional information on operators</a></td>
            </tr>
        </tbody>
        <tbody id="table-operators" class="table-toggleable-section">
            <tr>
                <td colspan="6">
                    <p>
                        <strong>[1] Operator unlock cost:</strong><br>
                        Original operators: 12,500 Renown or 300 R6 Credits each.<br>
                        DLC (Year 1, 2, and 3) operators: 25,000 Renown or 600 R6 Credits each.
                    </p>
                    <p>
                        Ubisoft estimates it takes 15 hours of play to acquire 12,500 renown. <br>The Year 1 and Year 2 operators can also be instantly unlocked in the Year 1 and Year 2 bundles for 2400 R6 Credits each (approx US$20).
                    </p>
                    <p>
                        <strong>[2] Starter Edition operator unlocks:</strong><br>
                        3 Attackers + 3 Defenders randomly unlocked from the following pool: <br>
                        Attackers: Ash, Thermite, Thatcher, Fuze, Sledge.<br>
                        Defenders: Rook, Mute, Smoke, Jager, Kapkan.
                    </p>
                </td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <th>Year 3 Season Pass</th>
                <!--Starter Edition-->
                <td class="none">Not included</td>
                <!--Standard Edition-->
                <td class="none">Not included</td>
                <!--Advanced Edition-->
                <td class="none">Not included</td>
                <!--Gold Edition (Year 3)-->
                <td class="included">Included</td>
                <!--Complete Edition-->
                <td class="included">Included</td>
            </tr>
            <tr>
                <td colspan="6" class="table-toggle"><a href="#" onclick="toggleTableSection(event, 'table-seasonpass')">Season Pass benefits</a></td>
            </tr>
        </tbody>
        <tbody id="table-seasonpass" class="table-toggleable-section">
            <tr>
                <th>New Year 3 operators</th>
                <td colspan="3" class="none">Not included</td>
                <td colspan="2" class="included">Included <br><small>with 7-day early access</small></td>
            </tr>
            <tr>
                <th>Season Pass exclusive cosmetics</th>
                <td colspan="3" class="none">Not included</td>
                <td colspan="2">
                    - 8 exclusive headgear and uniforms<br>
                    - R6 Charm
                </td>
            </tr>
            <tr>
                <th>Season Pass benefits</th>
                <td colspan="3" class="none">Not included</td>
                <td colspan="2">
                    - 10% discount on in-game purchases with Renown or R6 Credits<br>
                    - 5% additional Renown earned<br>
                    - +0.3% Alpha Pack chance
                </td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <th>Included R6 Credits</th>
                <td colspan="2" class="none">Not included</td>
                <td colspan="3" class="included">600 R6 Credits</td>
            </tr>
            <tr>
                <th>Outbreak Packs</th>
                <td colspan="2" class="none">Not included</td>
                <td colspan="3" class="included">10 Outbreak Collection Packs</td>
            </tr>
        </tbody>
    </table>
</div>

## Additional information

### Renown and R6 Credits

As you play the game, you will earn Renown. Renown can be used to unlock operators or other in-game content such as cosmetics. There is also another form of currency known as R6 Credits, which can be purchased with money. 

All operators can be unlocked using Renown or R6 Credits. The number of operators unlocked out of the box depends on the edition of the game owned. 

### Year 3 and the content release cycle

There are four seasons in a year, and a new season comes out approximately every 3 months. 2 operators are typically released per season. The Year 3 roadmap for Siege can be found on [the official Rainbow Six: Siege website](https://rainbow6.ubisoft.com/siege/en-us/game-info/roadmap.aspx). 

Season Passes are valid only for a year. Year 3 passes will expire 31 January 2019. 

### Alpha Packs and Outbreak Packs

Alpha Packs are loot packs containing cosmetic items. Alpha Packs are earned by playing the game, or by purchasing them with Renown. With every won match, your chances of winning an Alpha Pack increases. 

There are also time-limited Premium Packs. Outbreak Packs are a tyoe of premium pack, featuring [Outbreak](https://rainbow6.ubisoft.com/siege/en-us/news/152-318321-16/details-of-outbreak-event-revealed)-themed cosmetics. Premium packs can only be purchased with R6 Credits within the time period they are available.

All types of packs contain only cosmetic items, and do not affect gameplay.

