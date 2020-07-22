<!-- ### Hi there 👋 -->

<!-- ![Header](https://raw.githubusercontent.com/tusharpandey13/tusharpandey13/master/header.svg) -->

<!-- <img src="./header.svg"> -->

    	<div xmlns="http://www.w3.org/1999/xhtml">
    		<style>
    			@keyframes rotate {
    				0% {
    					transform: rotate(3deg);
    				}
    				100% {
    					transform: rotate(-3deg);
    				}
    			}

    			@keyframes gradientBackground {
    				0% {
    					background-position: 0% 50%;
    				}
    				50% {
    					background-position: 100% 50%;
    				}
    				100% {
    					background-position: 0% 50%;
    				}
    			}
    			@keyframes bgchange {
    			  from {
    			    background-color: transparent;
    			  }
    			  to {
    			    background-color: #ffb510;
    			  }
    			}

    			@keyframes reveal_opacity {
    			  from {
    			    opacity: 0;
    			  }
    			  to {
    			    opacity: 1;
    			  }
    			}

    			@keyframes shadow1 {
    			  0% {
    			    font-size: 10px;
    			  }
    			  30% {
    			    font-size: 15px;
    			  }
    			  100% {
    			    font-size: 12px;
    			  }
    			}
    			@keyframes text_reveal {
    			  from {

    			    color: transparent;
    			  }
    			  to {

    			    color: #012a36;
    			  }
    			}

    			@keyframes slide_reveal {
    			  from {
    			    transform: scaleX(0);

    			  }
    			  to {
    			    transform: scaleX(1);

    			  }
    			}

    			@keyframes slide_up {
    			  from {
    			    transform: translateX(0);
    			  }
    			  to {
    			    transform: translateX(calc(-50vw + 100% / 2 + 3rem));

    			  }
    			}

    			.container {
    				font-family:
    					system-ui,
    					-apple-system,
    					'Segoe UI',
    					Roboto,
    					Helvetica,
    					Arial,
    					sans-serif,
    					'Apple Color Emoji',
    					'Segoe UI Emoji';
    				display: flex;
    				flex-direction: column;
    				justify-content: center;
    				align-items: center;
    				margin: 0;
    				width: 100%;
    				height: 400px;
    				background: linear-gradient(-45deg, #fc5c7d, #6a82fb, #05dfd7);
    				background-size: 600% 400%;
    				animation: gradientBackground 10s ease infinite;
    				border-radius: 6px;
    				color: white;
    				text-align: center;
    			}

    			h1 {
    				font-size: 50px;
    				line-height: 1.3;
    				letter-spacing: 5px;
    				text-transform: uppercase;
    				text-shadow:
    					0 1px 0 #efefef,
    					0 2px 0 #efefef,
    					0 3px 0 #efefef,
    					0 4px 0 #efefef,
    					0 12px 5px rgba(0, 0, 0, 0.1);
    				animation: rotate ease-in-out 1s infinite alternate;
    			}

    			p {
    				font-size: 20px;
    				text-shadow: 0 1px 0 #efefef;
    				animation: 5s ease 0s normal forwards 1 fadeIn;
    			}

    			.bigtext{
    				position: relative;
    				display: flex;
    				flex-direction: column;
    				justify-content: center;
    				align-items: center;
    				height: 3rem;
    				padding: 0 1rem 0 1.5rem;
    				font-family: monospace;
    				font-weight: 500;
    			    letter-spacing: 0.7rem;
    			    font-size: 1.5rem;
    				color: transparent;
    				animation: bgchange cubic-bezier(0.44, 0.85, 0.42, 1) 2s, slide_reveal cubic-bezier(0.44, 0.85, 0.42, 1) 1s, text_reveal cubic-bezier(0.44, 0.85, 0.42, 1) 1s;
    				animation-delay: 0.5s, 0.5s, 1.5s, 3s;
    				animation-fill-mode: forwards, forwards, forwards, forwards;
    				transform-origin: left;
    				-webkit-touch-callout: none;
    				-webkit-user-select: none;
    				-khtml-user-select: none;
    				-moz-user-select: none;
    				-ms-user-select: none;
    				user-select: none;
    			}
    			.bigtext span {
    				display: flex;
    				flex-direction: column;
    				justify-content: center;
    				align-items: center;
    			}
    			.bigtext::before{
    				content: " ";

position: absolute;
top: 0;
right: 0;
bottom: 0;
left: 0;
opacity: 0;
box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.14), 0 1px 18px 0 rgba(0, 0, 0, 0.12), 0 3px 5px -1px rgba(0, 0, 0, 0.4);
animation: reveal_opacity cubic-bezier(0.44, 0.85, 0.42, 1) 1.5s;
animation-delay: 2s;
animation-fill-mode: forwards;
}
.bigtext:hover {
box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.14),0 9px 46px 8px rgba(0, 0, 0, 0.12), 0 3px 5px -1px rgba(0, 0, 0, 0.4);
}

    		</style>
    		<div class="container">
    			<div class="bigtext-C">
    				<div class="bigtext">
    					<span>TUSHAR PANDEY</span>
    				</div>
    			</div>

    			<!-- <h1> Tushar</h1> -->
    		</div>
    	</div>

<!--
**tusharpandey13/tusharpandey13** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
