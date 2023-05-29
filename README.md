# dSecure


.front {
	width: 400px;
	height: 300px;
	// border-radius: 25px;
	// border: 3px solid gold;
	// background: #fff;
	color: white;
	// transform: perspective(400px) rotateY(20deg) skew(5deg);
	//Bump it our from the edge of the window
	// margin: 5em;
	position: relative;
	//Center the Content
	display: flex;
	justify-content: center;
	align-items: left;
	flex-direction: column;
}
.front:before {
	position:absolute;
	content:'';
	top:0;
	left: 0;
	width: 100%;
	height: 100%;
	border-radius: 25px;
	border: 3px solid gold;
	background: blue;
	color: white;
	transform: perspective(400px) rotateY(20deg) skew(5deg);
	//Bump it our from the edge of the window
	// margin: 5em;
	//Center the Content
	z-index: -1;
}
