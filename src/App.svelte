<script>
	import Fa from 'svelte-fa'
	import { faAddressBook,faAddressCard,faAsterisk,faAward,faBan,faBell,faBellSlash,faBinoculars,faBook,faBookmark,faBookOpen,faBookReader,faCalendar,faCalendarAlt,faCalendarCheck,faCalendarDay,faCalendarMinus,faCalendarPlus,faCalendarTimes,faCalendarWeek,faCamera,faCameraRetro,faCertificate,faClipboard,faClipboardCheck,faClipboardList,faCog,faEdit,faExclamation,faExclamationCircle,faExclamationTriangle,faFlag,faFaucet,faHome,faInfo,faPencilAlt,faSave,faTasks,faToilet,faToiletPaper,faToiletPaperSlash,faVideo,faVideoSlash } from '@fortawesome/free-solid-svg-icons'
	import { faComment,faCommentDots,faCommentAlt,faComments,faQuoteLeft,faQuoteRight } from '@fortawesome/free-solid-svg-icons'
	import { faDesktop,faMobileAlt } from '@fortawesome/free-solid-svg-icons'
	//Housing
	import { faBath, faBed, faBrush, faFireExtinguisher } from '@fortawesome/free-solid-svg-icons'
</script>

<main>
	<h1>Font Awesome Project Icons</h1>
</main>

<article>
	<h1>Icons</h1>
	<section id="home">
		<h1>Home</h1>
		<div style="font-size: 2em; color: var(--followup-action-color)">
			<Fa icon={faHome}/>
		</div>
	</section>
	<section>
		<h2>Settings</h2>
	</section>
	<section>
		<h1>Checklist</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faTasks}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)">
				<Fa icon={faClipboardList}/>
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
	<section>
		<h2>Criteria</h2>
	</section>
	<section id="followup-actions">
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
		</div>
	</section>
	<section>
		<h1>Settings</h1>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)">
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
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Edit">
				<Fa icon={faEdit}/>
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
				<Fa icon={faPencilAlt}/>
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
		</div>
		<div class="horziontal">
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Save">
				<Fa icon={faSave}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Desktop">
				<Fa icon={faDesktop}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Mobile">
				<Fa icon={faMobileAlt}/>
			</div>
		</div>
	</section>
	<a name="calendar">calendar</a>
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
	<a name="comments">comments</a>
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
	<a name="housing">housing</a>
	<section id="housing">
		<h1>Housing</h1>
		<div class="horziontal">


			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Bath">
				<Fa icon={faBath}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Bed">
				<Fa icon={faBed}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Brush">
				<Fa icon={faBrush}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Fire Extinguisher">
				<Fa icon={faFireExtinguisher}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet">
				<Fa icon={faToilet}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet Paper">
				<Fa icon={faToiletPaper}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Toilet Paper Slash">
				<Fa icon={faToiletPaperSlash}/>
			</div>
			<div style="font-size: 2em; color: var(--followup-action-color)" tooltip="Faucet">
				<Fa icon={faFaucet}/>
			</div>
		</div>
	</section>
</article>
<article>
	<h1>free-solid-svg-icons</h1>
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
		font-size: 2em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
