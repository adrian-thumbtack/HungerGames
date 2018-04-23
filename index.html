<!DOCTYPE html>
<html>
<head>
<title>Hunger Games Simulator</title>
<link rel="shortcut icon" href="icon.png">
<link type="text/css" rel="stylesheet" href="styles.css">
<script type="text/javascript" src="items.js"></script>
</head>
<body>
<div id="background">
</div>
<div id="start">
	<div id="hungergames" class="header">
	<h1 class="title">The Hunger Games</h1>
	<button id="button" type="button" class="button"><span>Confirm</span></button>
</div>
	<div style="height: 10%;"></div>
	<div style="width: 60%; float: left;">
		<h2 id="heading">May the odds be ever in your favor!</h2>
		<label>How many participants?
			<input id="wow" type="number"/>
		</label>
		<br><br>
		<label>Two champions allowed?
			<input id="double" type="checkbox"/>
		</label>
		<br>
		<br>
	</div>
</div>
<div id="names">
	<div id="reaping" class="header">
	<h1 class="title">The Reaping</h1>
	<button id="confirmNames" type="button" class="button"><span>Confirm Names</span></button>	
	</div>
</div>

<div id="stats">
<div class="header"><h1 class="title">The Tributes</h1><button id="proceedOne" type="button" class="button"><span>Proceed</span></button></div>
</div>

<div id="day">
<div class="header"><h1 id="dayNum" class="title">Day </h1><button id="proceedTwo" type="button" class="button"><span>Proceed</span></button></div>
</div>

<div id="corn">
<div class="header"><h1 class="title">The Bloodbath</h1><button id = "proceedThree" type="button" class="button"><span>Proceed</span></button></div>
</div>

<div id="deaths">
<div class="header"><h1 class="title">Honor the Fallen</h1><button id="proceedFour" type="button" class="button"><span>Proceed</span></button></div>
<h2 id="cannon"> cannon shots can be heard in the distance</h2>
<h2>The following tributes have fallen:</h2>
</div>

<div id="winner">
<div class="header"><h1 class="title">The Champion</h1><button id="proceedFive" type="button" class="button"><span>Proceed</span></button></div>
<h2 id="declare"></h2>
<h2 id="champKills"></h2>
</div>

<div id="summary">
<div class="header"><h1>A Recap of The Hunger Games</h1></div>
<button id="restart" type="button" class="buttonTwo"><span>New Hunger Games</span></button>
<button id="same" type="button" class="buttonTwo"><span>Quarter Quell! Same Tributes Again!</span></button>
</div>

<script>
	var first = document.getElementById("start");
	var wow = document.getElementById("double");
	var press = document.getElementById("button");
	var stats = document.getElementById("stats");
	var names = document.getElementById("names");
	var mult, num;
	var allNames = [];
	var deathBools = [];
	var summary = [];
	var kills = [];
	var alreadyDead = [];
	var day = document.getElementById("day");
	var winner = document.getElementById("winner");
	var dayCounter = 0;
	var corn = document.getElementById("corn");
	var deaths = document.getElementById("deaths");
	var numDeaths = 0;
	var proPos = [];
	var finalSum = document.getElementById("summary");
	var inum = itemsToFind.length;
	var wnum = weapons.length;
	var mnum = melee.length;
	var snum = shelter.length;
	var cnum = cornucopia.length;
	var spnum = sponsor.length;
	var minum = misc.length;

	var pro = [];
	var playerItems = [];
	var health = [];

	var onClick = function(){
		names.style.visibility = "visible";
		mult = wow.checked;
		num = document.getElementById("wow").value;
		if(num < 2) {
			alert("You really want "+num+" participants?");
			return;
		}
		first.style.visibility = "hidden";
		pressed = false;

		for (var i=0; i<num; i++){
			var temp = document.createElement("div");
			var label = document.createElement("label");
			label.appendChild(document.createTextNode("Tribute name: "));
			var field = document.createElement("input");
			field.setAttribute("type","text");
			field.className = "newNames";
			label.appendChild(field);
			var wowselect = document.createElement("select");
			wowselect.className = "wowselect";
			var male = document.createElement("option");
			male.value = "him";
			male.textContent = "M";
			var female = document.createElement("option");
			female.value = "her";
			female.textContent = "F";
			wowselect.appendChild(male);
			wowselect.appendChild(female);
			temp.appendChild(label);
			temp.appendChild(wowselect);
			temp.appendChild(document.createElement("br"));
			temp.appendChild(document.createElement("br"));
			//names.insertBefore(temp, names.children[names.children.length-1]);
			names.appendChild(temp);
		}
	};

	function registerNames(){
		allNames = [];
		pro = [];
		proPos = [];
		var fields = document.getElementsByClassName("newNames");
		var wowselect = document.getElementsByClassName("wowselect");

		for (var i=0; i<num; i++){
			allNames.push(fields[i].value);
			pro.push(wowselect[i].value);
			if (wowselect[i].value === "him"){
				proPos.push("his");
			}
			else {
				proPos.push(wowselect[i].value);
			}
			deathBools.push(true);
			alreadyDead.push(true);
			health.push(2);
			kills.push(0);
			playerItems.push([]);
			var temp = document.createElement("div");
			var p = document.createElement("p");
			p.appendChild(document.createTextNode(allNames[i] + " ("));
			var span = document.createElement("span");
			span.appendChild(document.createTextNode("Alive"));
			span.style.color = "lime";
			span.className = "wowdead";
			p.appendChild(span);
			p.appendChild(document.createTextNode("): "));
			var spanTwo = document.createElement("span");
			spanTwo.appendChild(document.createTextNode("0 Kills"));
			spanTwo.className = "wowkills";
			p.appendChild(spanTwo);
			p.appendChild(document.createTextNode("; "));
			var spanThree = document.createElement("span");
			spanThree.appendChild(document.createTextNode("Healthy"));
			spanThree.className = "wowhp";
			p.appendChild(spanThree);
			temp.appendChild(p);
			temp.id = allNames[i];
			temp.className = "champion";
			stats.appendChild(temp);
		}
		names.style.visibility = "hidden";
		stats.style.visibility = "visible";
	}

	function deadHighlight(){
		var spans = document.getElementsByClassName("wowdead");

		for (var i=0; i<num; i++){
			if (!deathBools[i]){
				spans[i].textContent = "Dead";
				spans[i].style.color = "red";
			}
		}
	}

	function proceedToDay(){
		var checkForWinner = declareWinner();
		document.getElementById("dayNum").textContent = "Day " + dayCounter;
		if (checkForWinner){
		}
		else if (dayCounter === 0){
			cornucopiaNow();
			dayCounter++;
		}
		else if (dayCounter === 1){
			simulateDay();
			dayCounter++;
		}
		else {
			dayClear();
			simulateDay();
			dayCounter++;
		}
	}

	function toDeaths(){
		var deathCounter = 0;
		var cannon = document.getElementById("cannon");
		var temp = document.createElement("div");
		var p = document.createElement("p");
		for (var i=0; i<deathBools.length; i++){
			if (!deathBools[i] && alreadyDead[i]){
				deathCounter++;
				if (kills[i] === 1){
					p.appendChild(document.createTextNode(allNames[i] + ": 1 Kill"));
				}
				else {
					p.appendChild(document.createTextNode(allNames[i] + ": " + kills[i] + " Kills"));
				}
				p.appendChild(document.createElement("br"));
				alreadyDead[i] = false;
			}
		}

		cannon.textContent = deathCounter + " cannon shots can be heard in the distance";
		if (deathCounter === 1){
			cannon.textContent = "1 cannon shot can be heard in the distance";
		}

		temp.appendChild(p);
		deaths.appendChild(temp);
		corn.style.visibility = "hidden";
		day.style.visibility = "hidden";
		deaths.style.visibility = "visible";
	}

	function toStats(){
		var wowkills = document.getElementsByClassName("wowkills");
		var wowhp = document.getElementsByClassName("wowhp");
		deadHighlight();
		for (var i=0; i<kills.length; i++){
			if (kills[i] === 1){
				wowkills[i].textContent = "1 Kill";
			}
			else {
				wowkills[i].textContent = kills[i] + " Kills";
			}
			var healthmsg = "";
			switch(health[i]){
				case 0: 
					healthmsg = "Deceased";
					break;
				case 1: 
					healthmsg = "Injured";
					break;
				case 2: 
					healthmsg = "Healthy";
					break;
				case 3:
					healthmsg = "Supercharged";
					break;
				default:
					if(health[i] < 0) healthmsg = "Very Deceased (This is a bug, please tell us if you see this)";
					else healthmsg = "Superdupercharged";
			}
			wowhp[i].textContent = healthmsg;
		}
		deaths.removeChild(deaths.children[deaths.childElementCount-1]);
		deaths.style.visibility = "hidden";
		stats.style.visibility = "visible";
	}

	function simulateDay(){
		var done = [];
		var fates = [];

		for (var i=0; i<num; i++){
			if (deathBools[i]){
				done.push(false);
			}
			else {
				done.push(true);
			}
		}

		while(done.indexOf(false) != -1){
			var r = rand(num);
			while (done[r]){
				if (r === num-1){
					r = 0;
				}
				else {
					r++;
				}
			}

			var isAWinner = declareWinnerAgain();
			if (isAWinner){
				break;
			}
			done[r] = true;

			switch (options[rand(options.length)]){
				case "weapons":
					var w = rand(wnum);
					var f = weapons[w].charAt(0);
					var article = "a";
					if (f === 'a' || f === 'e' || f === 'i' || f === 'o'){
						article += "n";
					}
					fates.push(allNames[r] + " stumbles upon " + article + " " + weapons[w] + ".");
					playerItems[r].push(weapons[w]);
					if (weapons[w] === "melee"){
						w = rand(mnum);
						f = melee[w].charAt(0);
						if (f === 'a' || f === 'e' || f === 'i' || f === 'o'){
							article += "n";
						}
						fates[fates.length-1] = allNames[r] + " stumbles upon " + article + " " + melee[w] + ".";
						playerItems[r][playerItems[r].length-1] = melee[w];
					}
					break;
				case "items":
					var a = rand(2);
					if (a === 0){
						var q = rand(inum);
						playerItems[r].push(itemsToFind[q]);
						var f = itemsToFind[q].charAt(0);
						var article = "a";
						if (itemsToFind[q] === "Lapras"){
							fates.push("A wild Lapras has appeared. " + allNames[r] + " has caught it!");
						}
						else if (itemsToFind[q] === "Stalin mustache"){
							fates.push(allNames[r] + " has grown a Stalin mustache.");
						}
						else if (itemsToFind[q] === "one spaghetti"){
							fates.push(allNames[r] + " discovers a singular spaghetti lying on the ground.");	
						}
						else {
							if (f === 'a' || f === 'e' || f === 'i' || f === 'o'){
								article += "n";
							}
							fates.push(allNames[r] + " discovers " + article + " " + itemsToFind[q] + " lying on the ground.");
						}
						break;
					}
					else if (a === 1){
						var q = rand(spnum);
						var f = sponsor[q].charAt(0);
						var article = "a";
						if (f === 'a' || f === 'e' || f === 'i' || f === 'o'){
							article += "n";
						}
						if (sponsor[q] === "one spaghetti"){
							fates.push(allNames[r] + " receives a singular spaghetti from a sponsor");	
						}
						else {
							fates.push(allNames[r] + " receives " + article + " " + sponsor[q] + " from a sponsor");
						}
						playerItems[r].push(sponsor[q]);
						if (sponsor[q] === "empty box"){
							fates[fates.length-1] += ", because apparently the sponsor is a dick.";
							playerItems[r].pop();
						}
						else {
							fates[fates.length-1] += ".";
						}
						break;
					}
				case "use":
					if (playerItems[r].length === 0){
						done[r] = false;
					}
					else {
						var a = playerItems[r][0];
						var b;
						if (itemsThatGivePoints.indexOf(a) != -1){
							pleaseHeal(r);
						}
						var aMelee;
						if (weapons.indexOf(a) != -1 || melee.indexOf(a) != -1){
							if (melee.indexOf(a) != -1){
								aMelee = a;
								a = "melee";
							}
							b = killCauseAndEffect[killCauseAndEffect.indexOf(a) + 1];
							var q = liveChampion(r);
							var fate = rand(2);
							if (a === "melee" && fate === 0){
								fates.push(allNames[r] + " " + b + " " + allNames[q] + " with a " + aMelee + ".");
								xKillsY(r,q);
								done[q] = true;
								summary.push(fates[fates.length-1]);
							}
							else if (a === "melee" && fate === 1){
								injureTwo(r,q);
								if (!deathBools[q]){
									done[q] = true;
									fates.push(allNames[r] + " " + b + " " + allNames[q] + " with a " + aMelee + ".");
									summary.push(fates[fates.length-1]);
								}
								else {
									fates.push(allNames[r] + " almost whacks " + allNames[q] + " to death with a " + aMelee + ".");
								}
							}
							else if (b === "random mine" || fate === 0){
								if (b === "random mine"){
									var c = rand(2);
									if (c === 0){
										var s = liveChampion(r);
										if (s != q){
											fates.push(allNames[r] + " sets off a landmine that kills " + allNames[q] + " and " + allNames[s] + ".");
											deathBools[q] = false;
											deathBools[s] = false;
											done[q] = true;
											done[s] = true;
											kills[r] += 2;
										}
										else {
											fates.push(allNames[r] + " sets off a landmine that kills " + allNames[q] + ".");
											xKillsY(r,q);
											done[q] = true;
										}
									}
									else {
										fates.push(allNames[r] + " accidentally steps on " + proPos[r] + " own landmine.");
										xDies(r);
									}
								}
								else if (a === "frisbee"){
									fates.push(allNames[r] + " decapitates " + allNames[q] + " with a frisbee.");
									xKillsY(r,q);
									done[q] = true;
								}
								else if (a === "octobrush"){
									fates.push(allNames[r] + " splats " + allNames[q] + " with an octobrush.");
									xKillsY(r,q);
									done[q] = true;
								}
								else if (a === "paintball"){
									fates.push(allNames[r] + " " + b + " " + allNames[q] + " dies of needing paintballs.");
									xKillsY(r,q);
									done[q] = true;
								}
								else {
									fates.push(allNames[r] + " " + b + " " + allNames[q] + ".");
									xKillsY(r,q);
									done[q] = true;
								}
								summary.push(fates[fates.length-1]);
							}
							else if (fate === 1){
								var q = liveChampion(r);
								if (a === "frisbee"){
									injureTwo(r,q);
									if (!deathBools[q]){
										fates.push(allNames[r] + " fatally breaks " + allNames[q] + "\'s nose with a frisbee.");
										done[q] = true;
										summary.push(fates[fates.length-1]);
									}
									else {
										fates.push(allNames[r] + " breaks " + allNames[q] + "\'s nose with a frisbee.");
									}
								}
								else if (a === "tank"){
									injureTwo(r,q);
									if (!deathBools[q]){
										fates.push(allNames[r] + " runs over " + allNames[q] + " with " + proPos[r] + " tank, causing the death of " + allNames[q] + ".");
										done[q] = true;
										summary.push(fates[fates.length-1]);
									}
									else {
										fates.push(allNames[r] + " runs over " + allNames[q] + " with " + proPos[r] + " tank, but " + allNames[q] + " survives due to " + proPos[q] + " belief in the Flying Spaghetti Monster.");
									}
								}
								else {
									injureTwo(r,q);
									if (!deathBools[q]){
										fates.push(allNames[r] + " " + b);
										done[q] = true;
										summary.push(fates[fates.length-1]);
									}
									else {
										fates.push(allNames[r] + " " + injEffect[injEffect.indexOf(a)+1] + " " + allNames[q] + ".");
									}
								}
							}
						}
						else if (a === "House of the Seven Gables"){
							fates.push("The roof falls on " + allNames[r] + ".");
							xDies(r);
							summary.push(fates[fates.length-1]);
						}
						else if (a === "email"){
							b = causeAndEffect[causeAndEffect.indexOf(a)+1];
							fates.push(allNames[r] + " " + b + ".");
							xDies(r);
							summary.push(fates[fates.length-1]);
						}
						else if (a === "indescribable object"){
							var temp = rand(3);
							if (temp === 0){
								fates.push(allNames[r] + "\'s indescribable object explodes in a shower of glorious communism, killing " + pro[r] + ".");
								xDies(r);
								summary.push(fates[fates.length-1]);
							}
							else if (temp === 1){
								fates.push(allNames[r] + " throws " + proPos[r] + " indescribable object, which quickly disintegrates " + allNames[q] + ".");
								xKillsY(r,q);
								done[q] = true;
								summary.push(fates[fates.length-1]);
							}
							else {
								fates.push(allNames[r] + "\'s indescribable object sits there uselessly, so " + allNames[r] + " pollutes the ocean with it.");
							}
						}
						else if (a === "chocolate-covered cotton"){
							injureOne(r);
							if (!deathBools[r]){
								fates.push(allNames[r] + " gets terminal constipation from chocolate-covered cotton and dies.");
								xDies(r);
								summary.push(fates[fates.length-1]);
							}
							else {
								fates.push(allNames[r] + " gets indigestion from eating too much chocolate-covered cotton.");
							}
						}
						else if (a === "Agrawal star"){
							var q = liveChampion(r);
							fates.push(allNames[r] + "\'s Agrawal star causes " + allNames[q] + " to die of jealousy.");
							done[q] = true;
							summary.push(fates[fates.length-1]);
							xKillsY(r,q);
						}
						else if (a === "freeze ray"){
							var q = liveChampion(r);
							injureTwo(r,q);
							if (!deathBools[q]){
								fates.push(allNames[q] + " contracts hypothermia after being shot by " + allNames[r] + "\'s freeze ray and freezes to death.");
								done[q] = true;
								summary.push(fates[fates.length-1]);
							}
							else {
								fates.push(allNames[r] + " freezes " + allNames[q] + " with a freeze ray.");
							}
						}
						else if (a === "Lapras"){
							var q = liveChampion(r);
							fates.push(allNames[r] + " used Lapras against " + allNames[q] + ". " + allNames[q] + " fainted and subsequently died. It was super effective.");
							xKillsY(r,q);
							summary.push(fates[fates.length-1]);
							done[q] = true;
						}
						else if (a === "Stalin mustache"){
							var q = liveChampion(r);
							fates.push(allNames[r] + " sends " + allNames[q] + " to the gulag.");
							xKillsY(r,q);
							summary.push(fates[fates.length-1]);
							done[q] = true;
						}
						else {
							var z = causeAndEffect[causeAndEffect.indexOf(a)];
							var y = causeAndEffect[causeAndEffect.indexOf(a)+1];
							if (z === "poisonous fruit tree" || z === "bleach gummy bottle" || z === "tin of Donald Trump's bronzer" || z === "Emoji Movie on laserdisc"){
								fates.push(allNames[r] + " " + y + ".");
								summary.push(fates[fates.length-1]);
								xDies(r);
							}
							else if (y === "random chicken"){
								var x = rand(2);
								if (x === 0){
									fates.push(allNames[r] + " eats Ohio Fried Chicken.");
								}
								else if (x === 1){
									injureOne(r);
									if (!deathBools[r]){
										fates.push(allNames[r] + " dies of overeating Ohio Fried Chicken.");
										summary.push(fates[fates.length-1]);
									}
									else {
										fates.push(allNames[r] + " goes into a food coma from too much Ohio Fried Chicken.");
									}
								}
							}
							else if (y === "random bandaid"){
								var aa = rand(2);
								if (aa === 0){
									pleaseHeal(r);
									fates.push(allNames[r] + " gains one health point after using a used Band-Aid.");
								}
								else {
									fates.push(allNames[r] + " gets tetanus from a used Band-Aid and dies.");
									xDies(r);
									summary.push(fates[fates.length-1]);
								}
							}
							else if (y === "safe dating"){
								var q = liveChampion(r);
								fates.push(allNames[r] + " and " + allNames[q] + " practice safe dating.");
								health[r]++;
								health[q]++;
							}
							else {
								fates.push(allNames[r] + " " + y + ".");
							}
						}
						discardItem(r);
					}
					break;
				case "shelter":
					console.log("shelter");
					var a = shelter[rand(shelter.length)];
					var b = rand(2);
					fates.push(allNames[r] + " finds a convenient " + a);
					if (b === 0 && a === "House of the Seven Gables"){
						playerItems[r].push(a);
					}
					if (b === 0){
						fates[fates.length-1] += " and decides to use it as shelter.";
					}
					else if (b === 1){
						fates[fates.length-1] += ", but decides it is too dangerous.";
					}
					break;
				case "misc":
					var a = misc[rand(minum)];
					var q = liveChampion(r);
					if (a === "cries"){
						fates.push(allNames[r] + " cries " + pro[r] + "self to sleep.");
					}
					else if (a === "Disney star takes"){
						fates.push("A " + a + " " + allNames[r] + "\'s money.");
					}
					else if (a === "hides from"){
						fates.push(allNames[r] + " hides from " + allNames[q]);
					}
					else if (a === "eats"){
						if (deathBools.indexOf(false) === -1){
							fates.push(allNames[r] + " eats dirt.");
						}
						else {
							var d = rand(num);
							while (deathBools[d]){
								if (d === num-1){
									d = 0;
								}
								else {
									d++;
								}
							}
							fates.push(allNames[r] + " eats " + allNames[d] + "\'s dead body.");
						}
					}
					else if (a === "talks to"){
						fates.push(allNames[r] + " talks to " + allNames[q] + ".");
					}
					else if (a === "drops a rant against"){
						fates.push(allNames[r] + " drops a rant about " + allNames[q] + ".");
					}
					else if (a === "logs"){
						fates.push(allNames[r] + " places " + proPos[r] + " head between two inconspicuous suspended logs.");
					}
					else if (a === "changes genders"){
						fates.push(allNames[r] + " " + a + ".");
						if (pro[r] === "him"){
							pro[r] = "her";
							proPos[r] = "her";
						}
						else {
							pro[r] = "him";
							proPos[r] = "his";
						}
					}
					else if (a === "email"){
						fates.push(allNames[r] + " angrily emails finance club about not being on the A team.");
						playerItems[r].push("email");
					}
					else {
						fates.push(allNames[r] + " " + a + ".");
					}
					break;
				case "injury":
					var a = injury[rand(injury.length)];
					if (a === "triggered"){
						var q = liveChampion(r);
						injureTwo(q,r);
						fates.push(allNames[q] + " triggers " + allNames[r]);
						if (!deathBools[r]){
							fates[fates.length-1] += " to death.";
							summary.push(fates[fates.length-1]);
						}
						else {
							fates[fates.length-1] += ".";
						}
					}
					else if (a === "battles and wounds"){
						var q = liveChampion(r);
						injureTwo(r,q);
						if (!deathBools[q]){
							fates.push(allNames[r] + " battles and kills " + allNames[q] + ".");
							summary.push(fates[fates.length-1]);
						}
						else {
							fates.push(allNames[r] + " battles and wounds " + allNames[q] + ".");
						}
					}
					else if (a === "prank calls"){
						var q = liveChampion(r);
						injureTwo(r,q);
						if (!deathBools[q]){
							fates.push(allNames[r] + " fatally prank calls " + allNames[q] + ".");
							summary.push(fates[fates.length-1]);
						}
						else {
							fates.push(allNames[q] + " gets prank called by " + allNames[r] + ".");
						}
					}
					else {
						injureOne(r);
						if (!deathBools[r]){
							fates.push(allNames[r] + " " + a + " and dies.");
							summary.push(fates[fates.length-1]);
						}
						else {
							fates.push(allNames[r] + " " + a + ".");
						}
					}
					break;
				case "heal":
					if (health[r] === 1){
						health[r]++;
						fates.push(allNames[r] + " heals " + pro[r] + "self.");
					}
					else if (health.indexOf(1) === -1){
						done[r] = false;
					}
					else {
						q = liveChampion(r);
						health[q] = 2;
						fates.push(allNames[r] + " heals " + allNames[q] + ".");
					}
					break;
				case "death":
					var a = variousDeaths[rand(variousDeaths.length)];
					console.log("death");
					console.log(a);
					var q = liveChampion(r);
					if (a === "breaks"){
						fates.push(allNames[r] + " " + a + " " + allNames[q] + "\'s neck.");
						summary.push(fates[fates.length-1]);
						done[q] = true;
						xKillsY(r,q);
					}
					else if (a === "gets burned to death from"){
						fates.push(allNames[r] + " gets burned to death from " + allNames[q] + "\'s mixtape.");
						summary.push(fates[fates.length-1]);
						xKillsY(q,r);
					}
					else if (a === "hangs"){
						fates.push(allNames[r] + " hangs " + pro[r] + "self after being friendzoned by " + allNames[q] + ".");
						summary.push(fates[fates.length-1]);
						xDies(r);
					}
					else if (a === "yells \"woag wiag wiag\" at"){
						fates.push(allNames[r] + " " + a + " " + allNames[q] + ", causing " + allNames[q] + " to drop dead.");
						summary.push(fates[fates.length-1]);
						done[q] = true;
						xKillsY(r,q);
					}
					else if (a === "chokes on crabapples in cheeks"){
						fates.push(allNames[r] + " chokes on crabapples in " + proPos[r] + " cheeks.");
						xDies(r);
						summary.push(fates[fates.length-1]);
					}
					else if (a === "navy seals"){
						fates.push(allNames[r] + " calls in the US Navy SEALS, who kill " + allNames[q]);
						s = liveChampion(r);
						if (s != q){
							fates[fates.length-1] += " and " + allNames[s];
							done[s] = true;
							xKillsY(r,s);
							summary.push(fates[fates.length-1]);
						}
						else {
							fates[fates.length-1] += ".";
							summary.push(fates[fates.length-1]);
						}
						done[q] = true;
						xKillsY(r,q);
					}
					else if (a === "coat hanger"){
						fates.push(allNames[r] + " gets beat to death by " + proPos[r] + " mother\'s coat hanger.");
						xDies(r);
						summary.push(fates[fates.length-1]);
					}
					else if (a === "stream"){
						fates.push(allNames[r] + " said racial slurs on a Twitch livestream and got roasted to death.")
					}
					else if (a === "unsafe dating"){
						var lol = playerItems[r].indexOf("pack of condoms");
						var lol2 = playerItems[q].indexOf("pack of condoms");
						if (lol != -1 || lol2 != -1){
							fates.push(allNames[r] + " and " + allNames[q] + " practice safe dating.");
							if (lol != -1){
								for (var i=lol; i<playerItems[r].length-1; i++){
									playerItems[r][i] = playerItems[r][i+1];
								}
								playerItems[r].pop();
							}
							if (lol2 != -1){
								for (var i=lol2; i<playerItems[q].length-1; i++){
									playerItems[q][i] = playerItems[q][i+1];
								}
								playerItems[q].pop();
							}
						}
						else {
							fates.push(allNames[r] + " and " + allNames[q] + " die of AIDS after practicing unsafe dating.");
							deathBools[r] = false;
							deathBools[q] = false;
							done[q] = true;
							summary.push(fates[fates.length-1]);
							health[r] = 0;
							health[q] = 0;
						}
					}
					else if (doubleDeath.indexOf(a) != -1){
						if (a === "gets nuked from orbit by" || a === "gets memed to death by" || a === "succumbs to lethal peer pressure from"){
							fates.push(allNames[q] + " " + a + " " + allNames[r] + ".");
						}
						else {
							fates.push(allNames[r] + " " + a + " " + allNames[q] + ".");
						}
						summary.push(fates[fates.length-1]);
						done[q] = true;
						xKillsY(r,q);
					}
					else {
						fates.push(allNames[r] + " " + a + ".");
						summary.push(fates[fates.length-1]);
						xDies(r);
					}
			}
		}

		var temp = document.createElement("div");
		var par = document.createElement("p");

		while (fates.length > 0){
			par.appendChild(document.createTextNode(fates[0]));
			par.appendChild(document.createElement("br"));
			par.appendChild(document.createElement("br"));
			for (var j=0; j<fates.length-1; j++){
				fates[j] = fates[j+1];
			}
			fates.pop();
		}

		temp.appendChild(par);
		day.appendChild(temp);
		day.style.visibility = "visible";
		stats.style.visibility = "hidden";
	}

	function cornucopiaNow(){
		var done = [];
		var fates = [];
		var notDone = 0;

		for (var i=0; i<num; i++){
			done.push(false);
			notDone++;
		}


		while (notDone != 0){
			var r = rand(num);
			if (done[r]){
				while (done[r]){
					if (r === allNames.length-1){
						r = 0;
					}
					else {
						r++;
					}
				}
			}

			done[r] = true;
			notDone--;

			switch(cornucopia[rand(cnum)]){
				case "run":
					fates.push(allNames[r] + " runs away from the Cornucopia.");
					break;
				case "supply":
					var z = rand(inum);
					var article = "a";
					if (vowels.indexOf(itemsToFind[z].charAt(0)) != -1){
						article += "n";
					}
					fates.push(allNames[r] + " finds " + article + " " + itemsToFind[z] + " in the Cornucopia.");
					playerItems[r].push(itemsToFind[z]);
					break;
				case "weapon":
					var z = rand(wnum);
					var article = "a";
					if (vowels.indexOf(weapons[z].charAt(0)) != -1){
						article += "n";
					}
					fates.push(allNames[r] + " finds " + article + " " + weapons[z] + " in the Cornucopia.");
					playerItems[r].push(weapons[z]);
					if (fates[fates.length-1].indexOf("melee") > 0){
						z = rand(mnum);
						fates[fates.length-1] = allNames[r] + " finds a " + melee[z] + " in the Cornucopia.";
						playerItems[r][playerItems[r].length-1] = melee[z];
					}
					break;
				case "battle":
					if (notDone === 0){
						fates.push(allNames[r] + " runs away from the Cornucopia.");
						break;
					}
					else {
						var q = liveChampion(r);
						var enemy = allNames[q];
						var fate = rand(4);
						var ult = allNames[r] + " battles " + enemy + ". ";
						if (fate === 0){
							ult += allNames[r] + " defeats " + enemy + ", but decides to spare " + proPos[q] + " life.";
						}
						else if (fate === 1){
							ult += allNames[r] + " defeats and kills " + enemy + ".";
							xKillsY(r,q);
							summary.push(ult);
						}
						else if (fate === 2){
							ult += enemy + " defeats " + allNames[r] + ", but decides to spare " + proPos[r] + " life.";
						}
						else if (fate === 3){
							ult += enemy + " defeats and kills " + allNames[r] + ".";
							xKillsY(q,r);
							summary.push(ult);
						}
						done[q] = true;
						notDone--;
						fates.push(ult);
						break;
					}
			}
		}

		var temp = document.createElement("div");
		var p = document.createElement("p");

		for (var i=fates.length-1; i>=0; i--){
			p.appendChild(document.createTextNode(fates.pop()));
			p.appendChild(document.createElement("br"));
			p.appendChild(document.createElement("br"));
		}

		temp.appendChild(p);
		corn.appendChild(temp);
		stats.style.visibility = "hidden";
		corn.style.visibility = "visible";
	}

	function rand(x){
		return Math.floor(Math.random()*x);
	}

	function injureOne(x){
		if (health[x] > 1){
			health[x]--;
		}
		else {
			health[x] = 0;
			deathBools[x] = false;
		}
	}

	function injureTwo(x,y){
		if (health[y] > 1){
			health[y]--;
		}
		else {
			health[y] = 0;
			deathBools[y] = false;
			kills[x]++;
		}
	}

	function pleaseHeal(x){
		health[x]++;
	}

	function liveChampion(x){
		var y = rand(num);
		while (!deathBools[y] || y === x){
			if (y === num-1){
				y = 0;
			}
			else {
				y++;
			}
		}
		return y;
	}

	function discardItem(x){
		for (var i=0; i<playerItems[x].length-1; i++){
			playerItems[x][i] = playerItems[x][i+1];
		}
		playerItems[x].pop();
	}

	function xDies(x){
		deathBools[x] = false;
		health[x] = 0;
	}

	function xKillsY(x,y){
		deathBools[y] = false;
		kills[x]++;
		health[y] = 0;
	}

	function dayClear(){
		day.removeChild(day.children[day.childElementCount-1]);
	}

	function declareWinnerAgain(){
		var count = 0;
		
		for (var i=0; i<deathBools.length; i++){
			if (deathBools[i]){
				count++;
			}
		}
		
		if (count === 1){
			return true;
		}
		return false;
	}
	
	function declareWinner(){
		var count = 0;

		for (var i=0; i<deathBools.length; i++){
			if (deathBools[i]){
				count++;
			}
		}

		if (count === 1){
			document.getElementById("declare").innerHTML = "<strong>" + allNames[deathBools.indexOf(true)] + "</strong>";
			if (kills[deathBools.indexOf(true)] === 1){
				document.getElementById("champKills").textContent = kills[deathBools.indexOf(true)] + " Kill";
			}
			else {
				document.getElementById("champKills").textContent = kills[deathBools.indexOf(true)] + " Kills";
			}
			winner.style.visibility = "visible";
			stats.style.visibility = "hidden";
			return true;
		}
		else {
			return false;
		}
	}

	function toSummary(){
		var temp = document.createElement("div");
		var p = document.createElement("p");

		for (var i=0; i<summary.length; i++){
			p.appendChild(document.createTextNode(summary[i]));
			p.appendChild(document.createElement("br"));
		}
		var h = document.createElement("h3");
		var ach = document.createElement("p");
		h.appendChild(document.createTextNode(allNames[deathBools.indexOf(true)] + " is the champion!"));
		if ( kills[deathBools.indexOf(true)] === 0){
			ach.appendChild(document.createElement("br"));
			ach.appendChild(document.createTextNode("Achievement Get: Pacifist Run!"));
		}
		if ( kills[deathBools.indexOf(true)] >= Math.sqrt(deathBools.length)){
			ach.appendChild(document.createElement("br"));
			ach.appendChild(document.createTextNode("Achievement Get: Serial Killer!"));
		}
		if ( health[deathBools.indexOf(true)] > 2){
			ach.appendChild(document.createElement("br"));
			ach.appendChild(document.createTextNode("Achievement Get: Overdose!"));
		}
		if ( playerItems[deathBools.indexOf(true)].length > 4){
			ach.appendChild(document.createElement("br"));
			ach.appendChild(document.createTextNode("Achievement Get: Hoarder!"));
		}
		ach.style.fontSize = "large";
		ach.style.fontWeight = "bold";
		ach.appendChild(document.createElement("br"));
		ach.appendChild(document.createTextNode("Achievement Get: Tester!"));
		temp.appendChild(p);
		temp.appendChild(h);
		temp.appendChild(ach);
		finalSum.insertBefore(temp, finalSum.children[finalSum.childElementCount-2]);

		finalSum.style.visibility = "visible";
		winner.style.visibility = "hidden";
	}

	function clearGames(){
		allNames = [];
		deathBools = [];
		kills = [];
		alreadyDead = [];
		pro = [];
		proPos = [];
		playerItems = [];
		health = [];
		dayClear();
		dayCounter = 0;

		console.log(allNames);

		for (var i=0; i<num; i++){
			names.removeChild(names.children[names.childElementCount-1]);
		}

		first.style.visibility = "visible";
		visibleStuff();
	}

	function sameTributes(){
		dayCounter = 0;
		deathBools = [];
		kills = [];
		alreadyDead = [];
		playerItems = [];
		health = [];
		dayClear();
		visibleStuff();
	}

	function visibleStuff(){
		names.style.visibility = "visible";
		winner.style.visibility = "hidden";
		finalSum.style.visibility = "hidden";

		for (var i=0; i<num; i++){
			stats.removeChild(stats.children[stats.childElementCount-1]);
		}
		corn.removeChild(corn.children[corn.childElementCount-1]);

		finalSum.removeChild(finalSum.children[finalSum.childElementCount-3]);
		summary = [];
	}

	press.addEventListener("click",onClick);
	document.getElementById("confirmNames").addEventListener("click",registerNames);
	document.getElementById("proceedOne").addEventListener("click", proceedToDay);
	document.getElementById("proceedTwo").addEventListener("click", toDeaths);
	document.getElementById("proceedThree").addEventListener("click",toDeaths);
	document.getElementById("proceedFour").addEventListener("click",toStats);
	document.getElementById("proceedFive").addEventListener("click", toSummary);
	document.getElementById("restart").addEventListener("click", clearGames);
	document.getElementById("same").addEventListener("click", sameTributes);
</script>
</body>
</html>
