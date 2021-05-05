<script>
	import Fa from 'svelte-fa'
	import { faAddressBook,faAddressCard,faAsterisk,faAward,faBan,faBell,faBellSlash,faBinoculars,faBook,faBookmark,faBookOpen,faBookReader,faCalendar,faCalendarAlt,faCalendarCheck,faCalendarDay,faCalendarMinus,faCalendarPlus,faCalendarTimes,faCalendarWeek,faCamera,faCameraRetro,faCertificate,faClipboard,faClipboardCheck,faClipboardList,faCog,faEdit,faExclamation,faExclamationCircle,faExclamationTriangle,faFlag,faFaucet,faHome,faInfo,faPencilAlt,faSave,faTasks,faToilet,faToiletPaper,faToiletPaperSlash,faVideo,faVideoSlash } from '@fortawesome/free-solid-svg-icons'
	//Followup Actions
	import { faFileImage,faImage, faImages } from '@fortawesome/free-solid-svg-icons'
	//Users
	import { faUsers, faUsersCog, faUser,faUserCog, faUserFriends, faUserAlt,faUserCircle,faUserCheck } from '@fortawesome/free-solid-svg-icons'
	//Comments
	import { faComment,faCommentDots,faCommentAlt,faComments,faQuoteLeft,faQuoteRight,faThumbsDown, faThumbsUp} from '@fortawesome/free-solid-svg-icons'
	import { faDesktop,faMobileAlt } from '@fortawesome/free-solid-svg-icons'
	//Edit
	import { faToggleOff, faToggleOn, faCheckCircle, faCircle } from '@fortawesome/free-solid-svg-icons'
	import { faFilePdf, faSearch, faTrash,faTrashAlt } from '@fortawesome/free-solid-svg-icons'
	import { faPlus, faPlusCircle, faPlusSquare, faMinus, faMinusCircle, faMinusSquare } from '@fortawesome/free-solid-svg-icons'
	//Checklist
	import { faList,faListAlt,faListOl,faListUl } from '@fortawesome/free-solid-svg-icons'
	//House
	import { faCat, faChair, faCouch, faKey, faLightbulb, faSpider, faWheelchair, faWifi, faShower, faTv} from '@fortawesome/free-solid-svg-icons'
	import { faAccessibleIcon} from '@fortawesome/free-brands-svg-icons'
	//Housing Construction
	import { faBath, faBatteryEmpty, faBatteryFull,faBatteryHalf, faBatteryQuarter, faBatteryThreeQuarters, faBurn, faChargingStation,  faBed, faBrush,faDumpster, faDumpsterFire, faFireExtinguisher,faHammer,faHardHat,faPaintRoller, faScrewdriver, faSolarPanel, faTools, faToolbox, faTruckPickup, faWrench} from '@fortawesome/free-solid-svg-icons'
	import { faFan, faPlug, faPowerOff} from '@fortawesome/free-solid-svg-icons'
	// Landscaping
	import { faLeaf,faSeedling,faSun,faCloudSun, faCloudSunRain,faWater } from '@fortawesome/free-solid-svg-icons'
	// Place
	import { faMapMarker, faMapMarkerAlt } from '@fortawesome/free-solid-svg-icons'
	// Spinners
	import { faSpinner, faCircleNotch } from '@fortawesome/free-solid-svg-icons'
	// Synch
	import { faSync, faSyncAlt } from '@fortawesome/free-solid-svg-icons'
</script>

<main>
	<h1>Project Icons</h1>
</main>
<article>
	<section id="home">
		<h1>Home</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Home">
				<Fa icon={faHome}/>
			</div>
		</div>
	</section>
	<section>
		<h1>Checklist</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Tasks">
				<Fa icon={faTasks}/>
			</div>
		</div>
	</section>
	<section>
		<h2>Checkpoint</h2>
	</section>
	<section>
		<h1>Hold Point</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faExclamationTriangle}/>
			</div>
		</div>
	</section>
	<section>
		<h2>Workarea</h2>
	</section>
	<section>
		<h2>Project Location - Place</h2>
	</section>
	<section>
		<h1>Verification</h1>
		<div style="font-size: 2em; color: var(--followup-action-color)">
			<Fa icon={faClipboardCheck}/>
		</div>
	</section>
	<section id="criteria">
		<h1>Criteria</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Info">
				<Fa icon={faInfo}/>
			</div>
		</div>
	</section>
	<section id="followup-actions">
		<h1>Followup Actions</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Followup Action">
				<Fa icon={faAsterisk}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Camera take Photo of problem">
				<Fa icon={faCamera}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Images">
				<Fa icon={faImages}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Image">
				<Fa icon={faImage}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Upload File Image of problem">
				<Fa icon={faFileImage}/>
			</div>
		</div>
	</section>
	<section id="users">
		<h1>Users</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User">
				<Fa icon={faUserAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Users">
				<Fa icon={faUserFriends}/>
			</div>
<!--
			<div style="font-size: 2em; color: var(&#45;&#45;followup-action-color)" tooltip="Users">
				<Fa icon={faUsers}/>
			</div>
			<div style="font-size: 2em; color: var(&#45;&#45;followup-action-color)" tooltip="Users Settings">
				<Fa icon={faUsersCog}/>
			</div>
			<div style="font-size: 2em; color: var(&#45;&#45;followup-action-color)" tooltip="User">
				<Fa icon={faUser}/>
			</div>
			<div style="font-size: 2em; color: var(&#45;&#45;followup-action-color)" tooltip="User Settings">
				<Fa icon={faUserCog}/>
			</div>
			<div style="font-size: 2em; color: var(&#45;&#45;followup-action-color)" tooltip="User">
				<Fa icon={faUserCircle}/>
			</div>
			<div style="font-size: 2em; color: var(&#45;&#45;followup-action-color)" tooltip="User">
				<Fa icon={faUserCheck}/>
			</div>
			-->
		</div>
	</section>
	<section>
		<h1>Settings</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User and application settings">
				<Fa icon={faCog}/>
			</div>
		</div>
	</section>
	<section>
		<h1>Camera</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Camera">
				<Fa icon={faCamera}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Retro Camera">
				<Fa icon={faCameraRetro}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Video">
				<Fa icon={faVideo}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="No Video">
				<Fa icon={faVideoSlash}/>
			</div>
		</div>
	</section>
	<section>
		<h1>General</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Address Book">
				<Fa icon={faAddressBook}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Address Card">
				<Fa icon={faAddressCard}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCertificate}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faAward}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboard}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboardCheck}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboardList}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBell}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBellSlash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBinoculars}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Bookmark">
				<Fa icon={faBookmark}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBook}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBookOpen}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBookReader}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Desktop">
				<Fa icon={faDesktop}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Mobile">
				<Fa icon={faMobileAlt}/>
			</div>
		</div>
	</section>
	<section id="general-edit">
		<h1>General - Edit</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Pdf">
				<Fa icon={faFilePdf}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Pencil">
				<Fa icon={faPencilAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Edit">
				<Fa icon={faEdit}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Save">
				<Fa icon={faSave}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Search">
				<Fa icon={faSearch}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Trash">
				<Fa icon={faTrash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Trash">
				<Fa icon={faTrashAlt}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plus">
				<Fa icon={faPlus}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plus Circle">
				<Fa icon={faPlusCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plus Square">
				<Fa icon={faPlusSquare}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Minus">
				<Fa icon={faMinus}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Minus Circle">
				<Fa icon={faMinusCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Minus Square">
				<Fa icon={faMinusSquare}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toggle Off">
				<Fa icon={faToggleOff}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toggle On">
				<Fa icon={faToggleOn}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Check Circle">
				<Fa icon={faCheckCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Circle">
				<Fa icon={faCircle}/>
			</div>
		</div>
	</section>
	<section id="calendar">
		<h1>Calendar</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendar}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarCheck}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarTimes}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarDay}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarMinus}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarPlus}/>
			</div>

			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Weekly Calendar">
				<Fa icon={faCalendarWeek}/>
			</div>
		</div>
	</section>
	<section id="comments">
		<h1>Comments</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comment">
				<Fa icon={faComment}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comment">
				<Fa icon={faCommentDots}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comment">
				<Fa icon={faCommentAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comments">
				<Fa icon={faComments}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Left Quote">
				<Fa icon={faQuoteLeft}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Right Quote">
				<Fa icon={faQuoteRight}/>
			</div>
		</div>
	</section>
	<section id="house">
		<h1>House</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Bed">
				<Fa icon={faBed}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cat">
				<Fa icon={faCat}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Chair">
				<Fa icon={faChair}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Couch">
				<Fa icon={faCouch}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="TV">
				<Fa icon={faTv}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Wifi}">
				<Fa icon={faWifi}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Key">
				<Fa icon={faKey}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Wheel Chair">
				<Fa icon={faWheelchair}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Accessible">
				<Fa icon={faAccessibleIcon}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Bath">
				<Fa icon={faBath}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Shower">
				<Fa icon={faShower}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet">
				<Fa icon={faToilet}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fan">
				<Fa icon={faFan}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plug">
				<Fa icon={faPlug}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Lightbulb">
				<Fa icon={faLightbulb}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet Paper">
				<Fa icon={faToiletPaper}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet Paper Slash">
				<Fa icon={faToiletPaperSlash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Spider">
				<Fa icon={faSpider}/>
			</div>
		</div>
	</section>
	<section id="housing">
		<h1>Housing - Construction</h1>
		<div class="horziontal">
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Brush">
					<Fa icon={faBrush}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Dumpster">
					<Fa icon={faDumpster}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Dumpster Fire">
					<Fa icon={faDumpsterFire}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fire Extinguisher">
					<Fa icon={faFireExtinguisher}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Faucet">
					<Fa icon={faFaucet}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Hammer">
					<Fa icon={faHammer}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Hard Hat">
					<Fa icon={faHardHat}/>
				</div>
			</div>
			<div class="horziontal">
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Paint Roller">
					<Fa icon={faPaintRoller}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Screw driver">
					<Fa icon={faScrewdriver}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Tools">
					<Fa icon={faTools}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Tool Box}">
					<Fa icon={faToolbox}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Truck Pickup">
					<Fa icon={faTruckPickup}/>
				</div>
				<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Wrench}">
					<Fa icon={faWrench}/>
				</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Solar Panel">
				<Fa icon={faSolarPanel}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Empty">
				<Fa icon={faBatteryEmpty}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Full">
				<Fa icon={faBatteryFull}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Half">
				<Fa icon={faBatteryHalf}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Quarter">
				<Fa icon={faBatteryQuarter}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Three Quarters">
				<Fa icon={faBatteryThreeQuarters}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Burn">
				<Fa icon={faBurn}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Charging Station">
				<Fa icon={faChargingStation}/>
			</div>
		</div>
		<div class="horziontal">
			<div id="fan" style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fan">
				<Fa icon={faFan}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Light bulb">
				<Fa icon={faLightbulb}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plug">
				<Fa icon={faPlug}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Power Off">
				<Fa icon={faPowerOff}/>
			</div>
		</div>
	</section>
	<section id="landscaping">
		<h1>Landscaping</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Seedling">
				<Fa icon={faSeedling}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Leaf">
				<Fa icon={faLeaf}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Sun">
				<Fa icon={faSun}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cloud Sun">
				<Fa icon={faCloudSun}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cloud Sun Rain">
				<Fa icon={faCloudSunRain}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Water">
				<Fa icon={faWater}/>
			</div>
		</div>
	</section>
	<section id="place">
		<h1>Place</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Map Marker">
				<Fa icon={faMapMarker}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Map Marker Alt">
				<Fa icon={faMapMarkerAlt}/>
			</div>
		</div>
	</section>
	<section id="spinners">
		<h1>Spinners</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Spinner">
				<Fa icon={faSpinner}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Circle Notch">
				<Fa icon={faCircleNotch}/>
			</div>
		</div>
	</section>
	<section id="synch">
		<h1>Synch</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Sync">
				<Fa icon={faSync}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Sync Alt">
				<Fa icon={faSyncAlt}/>
			</div>
		</div>
	</section>
</article>
<main>
	<h1>Available Project Icons</h1>
	<p>Project Icons chosen from the following</p>
</main>
<article>
	<section id="alt-home">
		<h1>Home</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Home">
				<Fa icon={faHome}/>
			</div>
		</div>
	</section>
	<section>
		<h1>Checklist</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Tasks">
				<Fa icon={faTasks}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Unordered List">
				<Fa icon={faListUl}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboardList}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="List">
				<Fa icon={faList}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="List">
				<Fa icon={faListAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Ordered List">
				<Fa icon={faListOl}/>
			</div>
		</div>
	</section>
	<section>
		<h2>Checkpoint</h2>
	</section>
	<section>
		<h1>Hold Point</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBan}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faExclamationTriangle}/>
			</div>
		</div>
	</section>
	<section>
		<h2>Workarea</h2>
	</section>
	<section>
		<h2>Project Location - Place</h2>
	</section>
	<section>
		<h1>Verification</h1>
		<div style="font-size: 2em; color: var(--followup-action-color)">
			<Fa icon={faClipboardCheck}/>
		</div>
	</section>
	<section id="alt-criteria">
		<h1>Criteria</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Info">
				<Fa icon={faInfo}/>
			</div>
		</div>
	</section>
	<section id="alt-followup-actions">
		<h1>Followup Actions</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faAsterisk}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faExclamation}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faExclamationTriangle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faFlag}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faExclamationCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Thumbs Down">
				<Fa icon={faThumbsDown}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Thumbs Up">
				<Fa icon={faThumbsUp}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Camera">
				<Fa icon={faCamera}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Images">
				<Fa icon={faImages}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Image">
				<Fa icon={faImage}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="File Image">
				<Fa icon={faFileImage}/>
			</div>
		</div>
	</section>
	<section id="alt-users">
		<h1>Users</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Users">
				<Fa icon={faUsers}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Users Settings">
				<Fa icon={faUsersCog}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User">
				<Fa icon={faUser}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User Settings">
				<Fa icon={faUserCog}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User Friends">
				<Fa icon={faUserFriends}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User Alt">
				<Fa icon={faUserAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User">
				<Fa icon={faUserCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="User">
				<Fa icon={faUserCheck}/>
			</div>
		</div>
	</section>
	<section>
		<h1>Settings</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cog">
				<Fa icon={faCog}/>
			</div>
		</div>
	</section>
	<section>
		<h1>Camera</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Camera">
				<Fa icon={faCamera}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Retro Camera">
				<Fa icon={faCameraRetro}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Video">
				<Fa icon={faVideo}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="No Video">
				<Fa icon={faVideoSlash}/>
			</div>
		</div>
	</section>
	<section>
		<h1>General</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Address Book">
				<Fa icon={faAddressBook}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Address Card">
				<Fa icon={faAddressCard}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCertificate}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faAward}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboard}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboardCheck}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboardList}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBell}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBellSlash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBinoculars}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)"  tooltip="Bookmark">
				<Fa icon={faBookmark}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBook}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBookOpen}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faBookReader}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Desktop">
				<Fa icon={faDesktop}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Mobile">
				<Fa icon={faMobileAlt}/>
			</div>
		</div>
	</section>
	<section id="alt-general-edit">
		<h1>General - Edit</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Pdf">
				<Fa icon={faFilePdf}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Pencil">
				<Fa icon={faPencilAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Edit">
				<Fa icon={faEdit}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Save">
				<Fa icon={faSave}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Search">
				<Fa icon={faSearch}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Trash">
				<Fa icon={faTrash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Trash">
				<Fa icon={faTrashAlt}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plus">
				<Fa icon={faPlus}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plus Circle">
				<Fa icon={faPlusCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plus Square">
				<Fa icon={faPlusSquare}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Minus">
				<Fa icon={faMinus}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Minus Circle">
				<Fa icon={faMinusCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Minus Square">
				<Fa icon={faMinusSquare}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toggle Off">
				<Fa icon={faToggleOff}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toggle On">
				<Fa icon={faToggleOn}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Check Circle">
				<Fa icon={faCheckCircle}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Circle">
				<Fa icon={faCircle}/>
			</div>
		</div>
	</section>
	<section id="alt-calendar">
		<h1>Calendar</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendar}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarCheck}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarTimes}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarDay}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarMinus}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faCalendarPlus}/>
			</div>

			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Weekly Calendar">
				<Fa icon={faCalendarWeek}/>
			</div>
		</div>
	</section>
	<section id="alt-comments">
		<h1>Comments</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comment">
				<Fa icon={faComment}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comment">
				<Fa icon={faCommentDots}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comment">
				<Fa icon={faCommentAlt}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Comments">
				<Fa icon={faComments}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Left Quote">
				<Fa icon={faQuoteLeft}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Right Quote">
				<Fa icon={faQuoteRight}/>
			</div>
		</div>
	</section>
	<section id="alt-house">
		<h1>House</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Bed">
				<Fa icon={faBed}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cat">
				<Fa icon={faCat}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Chair">
				<Fa icon={faChair}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Couch">
				<Fa icon={faCouch}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="TV">
				<Fa icon={faTv}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Wifi}">
				<Fa icon={faWifi}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Key">
				<Fa icon={faKey}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Wheel Chair">
				<Fa icon={faWheelchair}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Accessible">
				<Fa icon={faAccessibleIcon}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Bath">
				<Fa icon={faBath}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Shower">
				<Fa icon={faShower}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet">
				<Fa icon={faToilet}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fan">
				<Fa icon={faFan}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plug">
				<Fa icon={faPlug}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Lightbulb">
				<Fa icon={faLightbulb}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet Paper">
				<Fa icon={faToiletPaper}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet Paper Slash">
				<Fa icon={faToiletPaperSlash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Spider">
				<Fa icon={faSpider}/>
			</div>
		</div>
	</section>
	<section id="alt-housing">
		<h1>Housing - Construction</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Brush">
				<Fa icon={faBrush}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Dumpster">
				<Fa icon={faDumpster}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Dumpster Fire">
				<Fa icon={faDumpsterFire}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fire Extinguisher">
				<Fa icon={faFireExtinguisher}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Faucet">
				<Fa icon={faFaucet}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Hammer">
				<Fa icon={faHammer}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Hard Hat">
				<Fa icon={faHardHat}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Paint Roller">
				<Fa icon={faPaintRoller}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Screw driver">
				<Fa icon={faScrewdriver}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Tools">
				<Fa icon={faTools}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Tool Box}">
				<Fa icon={faToolbox}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Truck Pickup">
				<Fa icon={faTruckPickup}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Wrench}">
				<Fa icon={faWrench}/>
			</div>
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Solar Panel">
				<Fa icon={faSolarPanel}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Empty">
				<Fa icon={faBatteryEmpty}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Full">
				<Fa icon={faBatteryFull}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Half">
				<Fa icon={faBatteryHalf}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Quarter">
				<Fa icon={faBatteryQuarter}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Battery Three Quarters">
				<Fa icon={faBatteryThreeQuarters}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Burn">
				<Fa icon={faBurn}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Charging Station">
				<Fa icon={faChargingStation}/>
			</div>
		</div>
		<div class="horziontal">
			<div id="alt-fan" style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fan">
				<Fa icon={faFan}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Light bulb">
				<Fa icon={faLightbulb}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Plug">
				<Fa icon={faPlug}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Power Off">
				<Fa icon={faPowerOff}/>
			</div>
		</div>
	</section>
	<section id="alt-landscaping">
		<h1>Landscaping</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Seedling">
				<Fa icon={faSeedling}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Leaf">
				<Fa icon={faLeaf}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Sun">
				<Fa icon={faSun}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cloud Sun">
				<Fa icon={faCloudSun}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Cloud Sun Rain">
				<Fa icon={faCloudSunRain}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Water">
				<Fa icon={faWater}/>
			</div>
		</div>
	</section>
	<section id="alt-place">
		<h1>Place</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Map Marker">
				<Fa icon={faMapMarker}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Map Marker Alt">
				<Fa icon={faMapMarkerAlt}/>
			</div>
		</div>
	</section>
	<section id="alt-spinners">
		<h1>Spinners</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Spinner">
				<Fa icon={faSpinner}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Circle Notch">
				<Fa icon={faCircleNotch}/>
			</div>
		</div>
	</section>
	<section id="alt-synch">
		<h1>Synch</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Sync">
				<Fa icon={faSync}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Sync Alt">
				<Fa icon={faSyncAlt}/>
			</div>
		</div>
	</section>
</article>
<main>
	<h1>Other Stuff</h1>
</main>
<article>
	<div style="font-size: 1em; color: var(--followup-action-color)">
		<Fa icon={faFlag}/>
	</div>
	<section>
	</section>
	<section>
	</section>
	<section>
	</section>
	<section>
	</section>
	<section>
	</section>
	<section>
		<Fa icon={faFlag} size="xs" class="followup-action"/>
		<Fa icon={faFlag} size="sm"/>
		<Fa icon={faFlag} size="lg"/>
		<Fa icon={faFlag} size="2x"/>
		<Fa icon={faFlag} size="2.5x"/>
		<Fa icon={faFlag} size="5x"/>
		<Fa icon={faFlag} size="7x"/>
		<Fa icon={faFlag} size="10x"/>
	</section>
	<section>
		<div>
			<Fa icon={faHome} fw style="background: mistyrose"/>
			Home
		</div>
		<div>
			<Fa icon={faInfo} fw style="background: mistyrose"/>
			Info
		</div>
		<div>
			<Fa icon={faBook} fw style="background: mistyrose"/>
			Library
		</div>
		<div>
			<Fa icon={faPencilAlt} fw style="background: mistyrose"/>
			Applications
		</div>
		<div>
			<Fa icon={faCog} fw style="background: mistyrose"/>
			Settings
		</div>
	</section>
</article>
<footer>
	<h1>Built using ... </h1>
	<ul>
		<li><a href="https://fontawesome.com/icons">Font Awesome Icons</a></li>
		<li><a href="https://cweili.github.io/svelte-fa/">svelte-fa</a></li>
	</ul>
</footer>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 2rem;
		font-weight: 100;
		margin: 1rem 1rem 0.5rem 1rem;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
