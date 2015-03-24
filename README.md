<h2>Welcome to my Playtesting Repo!</h2>
<p>This repo is soley for approved playtesters of the games I'm currently making. If you are here it means that you have been chosen as a responsible playtester for one of my games. <strong>Please remember to fill out a <a href="#playtest-form">playtest form</a></strong> after playing one or more of my games. It can only help me make better games or make my current games better. From this repo you can do the following:
  <ul>
    <li><a href="#games">Play free games!</a></li>
    <li>Help me improve my games by filling out a <a href="#playtest-form">playtest form</a></li>
  </ul>
	I've done my best to streamline this process for you by providing all the links below, but do note:
  <h4>DigiPen Copyright Notice</h4>
  <p>You are not to distribute the games I've made available to <strong>ANYONE</strong>. These games are copyright of DigiPen and programmed using their proprietary Zero Engine. Basically, you can play these games on your own, but do not share these games or attempt to sell them (honestly, why would you?).</p>
</p>

<h2>Games</h2>
<a href="#" name="games"></a>
<p>
	<a href="https://github.com/TheDevilsWaffle/Playtesting/blob/master/demo-up-and-down/Demo-UpAndDown-v01.exe?raw=true">
		<img src="https://github.com/TheDevilsWaffle/Playtesting/blob/master/promo-images/up-and-down-promo-image-2.png?raw=true" title ="Up+Down Demo v01" alt="Up+Down Demo v01" />
	</a>
	<sup>A puzzle platformer that is both single and multiplayer</sup>
</p>
<p> 
    <a href="https://github.com/TheDevilsWaffle/Playtesting/blob/master/demo-pile-of-corpses/Demo-PileOfCorpses-v05.exe?raw=true">
    	<img src="https://github.com/TheDevilsWaffle/Playtesting/blob/master/promo-images/pile-of-corpses-promo-image-2.png?raw=true" alt="Pile of Corpses v05" title="Pile of Corpses v05" />
    </a>
	<sup>A casual-arcade game where you fling falling corpses into coffins for points!</sup>
</p>
<p><strong>Special Note:</strong> All games run only on a <em>Windows environment (XP/Vista/7/8)</em> and you will need either a <em>keyboard</em> or <em>USB XBox gamepad</em> plugged into your computer in order to play. <strong>XBox gamepad is HIGHLY RECOMMENDED</strong>.</p>
</p>

<h2>Playtest Forms</h2>
<a href="#" name="playtest-form"></a>
<p>Would you like to have a part in improving my games? Please do me a favor and respond to me after playing my games by using the google forms below (do not worry, your response will be annonymous and I will not know who you are).
<p>
	<a href="">
		<img src="https://github.com/TheDevilsWaffle/Playtesting/blob/master/promo-images/upAndDown-PlaytestForms.png?raw=true" title ="Up+Down Playtest Form" alt="Up+Down Demo Playtest Form" />
	</a>
</p>
<p> 
    <a href="">
    	<img src="https://github.com/TheDevilsWaffle/Playtesting/blob/master/promo-images/PileOfCorpses-PlaytestForms.png?raw=true" alt="Pile of Corpses Playtest Form" title="Pile of Corpses Playtest Form" />
	</a>
</p>
<p>Your response will be completely anonymous so feel free to tell me exactly what you think! Thank you for helping me out in my adventures in game design!</p>
</p>

# Changelog
<ul>
	<li>UP AND DOWN - VERSION 01 - 03/20/2015</li>
		<ul>
			<li>Initial Release</li>
		</ul>
	<li>PILE OF CORPSES - VERSION 05 - 03/07/2015</li>
	    <ul>
	    	<li>Bodies decay over time.
	        	<br />  |----corpses now start off fresh, rot, and then decay to a point where they fill up the arena and cannot be interacted with. Bodies will change appearence to a skeleton and flash red/purple to indicate you are losing time to score points with this corpse.
	      	</li>
	   		<li>Fixed minor collision issues with the tilemap.
	        	<br />  |----Used to be able to fling corpses through the tilemap on accident.
	      	</li>
	      	<li>Planting your shovel on a corpse now highlights this corpse so that the player can easier see which corpse they are targeting.
	        	<br />  |----Not completely perfect, but it works.
	      	</li>
	      	<li>Changed physics for bodies.
	        	<br />  |----you can now collide with bodies and they have a bit more heft now.
	      	</li>
	      	<li>Bodies now drop slower.
	        	<br />  |----Bodies previously dropped every 1 - 5 seconds, but now it is 7 - 10 seconds.
	      	</li>
	      	<li>Bodies drop upon points being scored.
	        	<br />  |----for every 1000 points you score, more bodies drop.
	      	</li>
	      	<li>Minor adjustment to positioning of submenus and gameover text.
	        	<br />  |----They used to clip before.
	      	</li>
	      	<li>Minor adjustment to positioning of game camera.
	        	<br />  |----I just didn't like it.
	      	</li>
	      	<li>Minor adjustment to positioning of submenus and gameover text.
	        	<br />  |----They used to clip before.
	      	</li>
	      	<li>Player now jumps slightly higher
	        	<br />  |----20% higher, to be exact.
	      	</li>
	      	<li>Fixed major bug with corpses transitioning to unmovable piles while player was targeting this corpse causing a game crash.
	        	<br />  |----game will now kick you out of shovel plant mode, destroy the highlight, and remove the press X graphic if it exists.
	      	</li>
	    </ul>
	</li>
  	<li>VERSION 04 - 02/16/2015</li>
	    <ul>
	      	<li>Added keyboard support.
	        	<br />  |----Not ideal, but it works. Angle of flinging is confined to a set angle set to make things less complicated.
	      	</li>
	      	<li>Updated controls menu to reflect new keyboard controls.
	        	<br />  |----New art assets that dynamically change if there is a gamepad plugged in or not.
	      	</li>
	    </ul>
	</li>
</ul>
