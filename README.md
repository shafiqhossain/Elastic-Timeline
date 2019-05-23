# Elastic-Timeline
Display timeline with elastic expand

This is an exmple, how you can implement elastic timeline display when you scroll down the page.
This is based on Drupal 7.

You can add the log, by calling:
<code>activity_log($type, $title, $message, $nid, $uid)</code>

$type: Type of log<br>
$title: Title to display about the log<br>
$message: Detail of the log<br>
$nid: Node ID<br>
$uid: Optionally user id. If not provided, will add current logged in user id.<br>

<img src="screenshot.jpg" alt="screenshot" />
