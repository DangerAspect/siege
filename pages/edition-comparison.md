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
        table-layout: fixed;
    }
    .sticky-header{
        position: sticky;
        top: 0;
    }
    .sticky-header th{
        background-color: #0e0f12;
    }
    .features{
        width: 12rem;
    }
    .editions{
        font-size: 1.5rem;
        text-transform: uppercase;
        letter-spacing: 0.1ch;
    }
    .editions strong{
        font-weight: 500;
    }
    .edition-deluxe{
        background-color: #85241d !important;
    }
    .edition-gold{
        background-color: #b83 !important;
    }
    .edition-ultimate{
        background-color: #646464 !important;
    }
    .table-subheader{
        font-weight: normal;
        color: #ccc;
    }
    .table-text{
        padding: 0 2rem;
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

The following is a detailed comparison of the various editions available when purchasing Rainbow Six: Siege. This page has been updated for <a href="https://rainbow6.ubisoft.com/siege/en-us/news/152-344167-16/rainbow-six-siege-year-4-editions-launching-february-12">the changes made to game editions at the start of Year 4</a>, including the removal of Starter Edition.</p>

Rainbow Six: Siege allows unlocking all gameplay content including maps and operators simply through in-game progression. All maps and weapon attachments are instantly unlocked for all players out of the box. 

Additional information and context are provided after the table below. 

<div class="overflow-container">
    <table>
        <thead class="sticky-header">
            <tr>
                <th class="features">Feature</th>
                <th class="editions edition-base font-header">
                    <strong>Base</strong> Game
                </th>
                <th class="editions edition-deluxe font-header">
                    <strong>Deluxe</strong> Edition
                </th>
                <th class="editions edition-gold font-header">
                    <strong>Gold</strong> Edition
                </th>
                <th class="editions edition-ultimate font-header">
                    <strong>Ultimate</strong> Edition
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>Summary</th>
                <td> <!--Base Edition-->
                    The normal base edition of the game
                </td>
                <td> <!--Deluxe Edition-->
                    Base edition + 8 Year 1 operators unlocked
                </td>
                <td> <!--Gold Edition-->
                    Deluxe Edition + the Year 4 Pass
                </td>
                <td> <!--Ultimate Edition-->
                    Base edition + all Year 1 to 4 operators unlocked + Year 4 pass
                </td>
            </tr>
            <tr>
                <th>Maps</th>
                <td class="included" colspan="4">All maps are available to all players regardless of editions</td>
            </tr>
            <tr>
                <th>Operators</th>
                <td> <!--Base Edition-->
                    <div class="table-emphasis"><em>0</em> unlocked</div>
                </td>
                <td> <!--Deluxe Edition-->
                    <div class="table-emphasis"><em>8</em> unlocked</div>
                </td>
                <td> <!--Gold Edition-->
                    <div class="table-emphasis"><em>16</em> unlocked</div>
                </td>
                <td> <!--Ultimate Edition-->
                    <div class="table-emphasis"><em>32</em> unlocked</div>
                </td>
            </tr>
            <tr>
                <th class="table-subheader">(Base)</th>
                <td class="none" colspan="4">Unlockable for 500 to 2000 Renown each.</td>
            </tr>
            <tr>
                <th class="table-subheader">(Year 1)</th>
                <td class="none">Not included</td>
                <td class="included">8 Year 1 operators</td>
                <td class="included">8 Year 1 operators</td>
                <td class="included">8 Year 1 operators</td>
            </tr>
            <tr>
                <th class="table-subheader">(Year 2)</th>
                <td class="none" colspan="3">Not included</td>
                <td class="included">8 Year 2 operators</td>
            </tr>
            <tr>
                <th class="table-subheader">(Year 3)</th>
                <td class="none" colspan="3">Not included</td>
                <td class="included">8 Year 3 operators</td>
            </tr>
            <tr>
                <th class="table-subheader">(Year 4)</th>
                <td class="none" colspan="2">Not included</td>
                <td class="included">8 Year 4 operators</td>
                <td class="included">8 Year 4 operators</td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <td colspan="5" class="table-toggle"><a href="#" onclick="toggleTableSection(event, 'table-operators')">Operator unlock information</a></td>
            </tr>
        </tbody>
        <tbody id="table-operators" class="table-toggleable-section">
            <tr>
                <td class="table-text" colspan="5">
                    <p>
                        <strong>Base operators:</strong><br>
                        The first operator from each CTU (e.g. GIGN, FBI SWAT .etc) costs 500 Renown. The second will cost 1000, third 1500, and fourth 2000 Renown.
                    </p>
                    <p>
                        <strong>DLC operators:</strong><br> 
                        Between 10,000 and 25,000 Renown depending on the operator's original release date. <br>
                        See <a href="/operatorprices">the DLC Operator Unlock Prices page</a> for a list of operators and their current unlock prices
                    </p>
                </td>
            </tr>
            <tr>
                <td class="table-text" colspan="5">
                    <p>
                        Ubisoft estimates it takes 15 hours of play to acquire 12,500 Renown. <br>
                        The Year 1 and Year 2 operators can also be instantly unlocked in the Year 1 and Year 2 bundles for 2400 R6 Credits each (approx US$20).
                    </p>
                </td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <th>Year 4 Pass</th>
                <!--Base Edition-->
                <td class="none">Not included</td>
                <!--Deluxe Edition-->
                <td class="none">Not included</td>
                <!--Gold Edition-->
                <td class="included">Included</td>
                <!--Ultimate Edition-->
                <td class="included">Included</td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <td colspan="5" class="table-toggle"><a href="#" onclick="toggleTableSection(event, 'table-pass')">Year 4 Pass benefits</a></td>
            </tr>
        </tbody>
        <tbody id="table-pass" class="table-toggleable-section">
            <tr>
                <td class="table-text" colspan="5">
                    <p>
                        <strong>Year 4 operators</strong>: 
                        Included, with 7-day early access
                    </p>
                    <p>
                        <strong>Included R6 Credits</strong>: 
                        600 R6 Credits
                    </p>
                    <p>
                        <strong>Cosmetic items</strong>: 
                        8 headgear and uniforms, and the Lava Six charm
                    </p>
                    <p>
                        <strong>VIP membership</strong>:<br>
                        - 10% discount on in-game purchases with Renown or R6 Credits<br>
                        - 5% additional Renown earned<br>
                        - +0.3% Alpha Pack chance
                    </p>
                </td>
            </tr>
        </tbody>
    </table>
</div>

## Additional information

### Renown and R6 Credits

As you play the game, you will earn Renown. Renown can be used to unlock operators or other in-game content such as cosmetics. There is also another form of currency known as R6 Credits, which can be purchased with money. 

All operators can be unlocked using Renown or R6 Credits. The number of operators unlocked out of the box depends on the edition of the game owned. 

### Years, seasons, and the content release cycle

There are four seasons in a year, and a new season comes out approximately every 3 months. 2 operators are typically released per season. The Year 3 roadmap for Siege can be found on [the official Rainbow Six: Siege website](https://rainbow6.ubisoft.com/siege/en-us/game-info/roadmap.aspx). 

Year Passes are valid only for a year. The Year 4 Pass will expire 31 January 2020. 

### Alpha Packs

Alpha Packs are loot packs containing cosmetic items. Alpha Packs are earned by playing the game, or by purchasing them with Renown. With every won match, your chances of winning an Alpha Pack increases. 

All types of packs contain only cosmetic items, and do not affect gameplay.

