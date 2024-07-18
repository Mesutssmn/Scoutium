<div style="border-radius: 10px; overflow: hidden; text-align: center;">
    <img src="https://www.girisimhaber.com/uploads/image/post/_diger201807/Scoutium.jpg" alt="scotium" width="900"></div>

<div style="border-radius: 40px; border: #5E5772 solid; padding: 12px; background-color: #0654; font-size: 150%; text-align: left;">
    
<h4 align="left"><font color='#30000' size=5%>To Do :</font></h4>
    
<li> Cleaning dataset for classification</li>
    
<li> Some analysis and statistics</li>
    
<li> ML, ANN
    
    

<h3 align="left"><font color='#300000' size=5%>ABOUT DATA:</font></h3>

The dataset from Scoutium consists of information about football players observed during matches, including the players' characteristics and the scouts' evaluations of these players, as well as the rated features and scores of the players within the match.
</div>
<div style="border-radius: 10px; overflow: hidden; text-align: center;">
    <img src="https://i.ytimg.com/vi/GCKuxyKAbVc/maxresdefault.jpg" alt="scotium" width="900"></div>


<div style="font-family: Arial, sans-serif; line-height: 1.6; background-color: #0654; color: #333; padding: 20px;">

<h1 style="color: #2c3e50;">Business Problem</h1>
<p>Predicting which class (average, highlighted) a football player belongs to based on the ratings given by scouts on the players' attributes.</p> 
</div>

<div style="font-family: Arial, sans-serif; line-height: 1.6; background-color: #0654; color: #333; padding: 20px;">
<h2 style="color: #2c3e50;">About Dataset</h2>
<p>The dataset consists of information from Scoutium, containing ratings of football players' attributes observed during matches and evaluated by scouts.</p>

<h2 style="color: #2c3e50;">scoutium_attributes</h2>
<p><strong>8 Variables, 10,730 Observations, 527 KB</strong></p>
<ul>
<li><strong>task_response_id:</strong> The set of evaluations by a scout for all players in a team during a match.</li>
<li><strong>match_id:</strong> The ID of the match.</li>
<li><strong>evaluator_id:</strong> The ID of the evaluator (scout).</li>
<li><strong>player_id:</strong> The ID of the player.</li>
<li><strong>position_id:</strong> The ID of the position the player played in that match.
<ul>
<li>1: Goalkeeper</li>
<li>2: Center-back</li>
<li>3: Right-back</li>
<li>4: Left-back</li>
<li>5: Defensive midfielder</li>
<li>6: Central midfielder</li>
<li>7: Right winger</li>
<li>8: Left winger</li>
<li>9: Attacking midfielder</li>
<li>10: Forward</li>
</ul>
</li>
<li><strong>analysis_id:</strong> The set of attribute evaluations by a scout for a player in a match.</li>
<li><strong>attribute_id:</strong> The ID of each attribute evaluated for the players.</li>
<li><strong>attribute_value:</strong> The value (score) given by a scout for a player's attribute.</li>
</ul>

<h2 style="color: #2c3e50;">scoutium_potential_labels</h2>
<p><strong>5 Variables, 322 Observations, 12 KB</strong></p>
<ul>
<li><strong>task_response_id:</strong> The set of evaluations by a scout for all players in a team during a match.</li>
<li><strong>match_id:</strong> The ID of the match.</li>
<li><strong>evaluator_id:</strong> The ID of the evaluator (scout).</li>
<li><strong>player_id:</strong> The ID of the player.</li>
<li><strong>potential_label:</strong> The final decision label by a scout for a player in a match (target variable).</li>
</ul>

</div>
