<p>This is a quick project I put together in effort to learn HTML5's AudioContext.  It was inspired, and named after, Brian Eno's "Music for Airports".  Thanks to the following tutorials:</p>
	<ul>
		<li><a href="https://www.html5rocks.com/en/tutorials/webaudio/intro/" target="_blank">Getting Started with Web Audio API - HTML5 Rocks</a></li>
		<li><a href="https://modernweb.com/2013/10/28/audio-synthesis-in-javascript/" target="_blank">Audio Synthesis in JavaScript</a></li>
		<li><a href="https://codepen.io/keithclark/pen/zqcEd" target="_blank">Thanks to this site for the starfield css!</a></li>
		<li><a href="http://www.colorzilla.com/gradient-editor/" target="_blank">Planet gradients created using this tool.</a></li>
		<li><a href="https://paulbakaus.com/tutorials/html5/web-audio-on-ios/" target="_blank">Thanks to this site for iOS compatibility.</a></li>
	</ul>
	<p>How it works:</p>
	<p>Each destination has a defined set of notes.  Several random generators then determine how often to play a note, what note to play, and how long to sustain it.<p>
	Options:
	<ul>
		<li>Destination: note set</li>
		<li>Density: Frequency of note selection</li>
		<li>Drift: Stay in current set or drift to others</li>
		<!--<li>Announcements: If supported, use speech synthesis to announce destination</li>-->
	</ul>
	<p>Note: Due to Internet Explorer/Edge lack of support for WebAudio, this will not work in Microsoft browsers.</p>
