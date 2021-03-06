Userscripts
===========

A collection of my client-side userscripts.  

## Table of Contents

  * [IP.Board](#ipboard)
    * [`IP.Board_Auto-Save_Posts.user.js`](#ipboard_auto-save_postsuserjs-more)
    * [`IP.Board_Automatic_Notifications.user.js`](#ipboard_automatic_notificationsuserjs)
    * [`IP.Board_Custom_Avatars.user.js`](#ipboard_custom_avatarsuserjs)
    * [`IP.Board_Forum_Cleanup.user.js`](#ipboard_forum_cleanupuserjs)
    * [`IP.Board_Hide_Gender_in_Miniprofies.user.js`](#ipboard_hide_gender_in_miniprofiesuserjs)
    * [`IP.Board_Hide_Ignored_Post_Notices.user.js`](#ipboard_hide_ignored_post_noticesuserjs)
    * [`IP.Board_Isolate_Posts_by_User.user.js`](#ipboard_isolate_posts_by_useruserjs-more)
    * [`IP.Board_Lockpick_Quotes.user.js`](#ipboard_lockpick_quotesuserjs)
    * [`IP.Board_Member_Nicknames.user.js`](#ipboard_member_nicknamesuserjs-more)
    * [`IP.Board_Navigation_Shortcuts.user.js`](#ipboard_navigation_shortcutsuserjs-more)
    * [`IP.Board_Plaintext_BBCode.user.js`](#ipboard_plaintext_bbcodeuserjs-more)
    * [`IP.Board_Post_Loss_Prevention.user.js`](#ipboard_post_loss_preventionuserjs)
    * [`IP.Board_Post_Style.user.js`](#ipboard_post_styleuserjs-more)
    * [`IP.Board_Prevent_Video_Preload.user.js`](#ipboard_prevent_video_preloaduserjs)
    * [`IP.Board_Quote_Search_Results.user.js`](#ipboard_quote_search_resultsuserjs)
    * [`IP.Board_True_Ignore.user.js`](#ipboard_true_ignoreuserjs)
  * [IP.Chat](#ipchat)
    * [`IP.Chat-Specific_Theme.user.js`](#ipchat-specific_themeuserjs)
    * [`IP.Chat_Auto-Resizing_Popup.user.js`](#ipchat_auto-resizing_popupuserjs)
    * [`IP.Chat_Convert_Smilies_to_Text.user.js`](#ipchat_convert_smilies_to_textuserjs-more)
    * [`IP.Chat_Extension.user.js`](#ipchat_extensionuserjs-more)
    * [`IP.Chat_Ignore.user.js`](#ipchat_ignoreuserjs-more)
    * [`IP.Chat_Kick_Notice.user.js`](#ipchat_kick_noticeuserjs)
    * [`IP.Chat_Logs.user.js`](#ipchat_logsuserjs-more)
    * [`IP.Chat_Nickname_Users.user.js`](#ipchat_nickname_usersuserjs-more)
    * [`IP.Chat_Pings.user.js`](#ipchat_pingsuserjs-more)
    * [`dice_concise.user.js`](#dice_conciseuserjs-more)
  * [XenForo](#xenforo)
    * [`XenForo_Alerts_in_Page_Title.user.js`](#xenforo_alerts_in_page_titleuserjs)
    * [`XenForo_Auto-applying_Macros.user.js`](#xenforo_auto-applying_macrosuserjs-more)
    * [`XenForo_Auto-refresh_Users_Viewing_Thread.user.js`](#xenforo_auto-refresh_users_viewing_threaduserjs)
    * [`XenForo_Avatar_Preview.user.js`](#xenforo_avatar_previewuserjs-more)
    * [`XenForo_Block_Signatures.user.js`](#xenforo_block_signaturesuserjs-more)
    * [`XenForo_Expanded_Search_Results.user.js`](#xenforo_expanded_search_resultsuserjs-more)
    * [`XenForo_Hide_Gender_in_Miniprofiles.user.js`](#xenforo_hide_gender_in_miniprofilesuserjs)
    * [`XenForo_Isolate_Posts_by_User.user.js`](#xenforo_isolate_posts_by_useruserjs-more)
    * [`XenForo_Lockpick_Quotes.user.js`](#xenforo_lockpick_quotesuserjs)
    * [`XenForo_Member_Nicknames.user.js`](#xenforo_member_nicknamesuserjs-more)
    * [`XenForo_Message_Archiver.user.js`](#xenforo_message_archiveruserjs-more)
    * [`XenForo_Navigation_Shortcuts.user.js`](#xenforo_navigation_shortcutsuserjs-more)
    * [`XenForo_Plaintext_BBCode.user.js`](#xenforo_plaintext_bbcodeuserjs-more)
    * [`XenForo_Post_Style.user.js`](#xenforo_post_styleuserjs-more)
    * [`XenForo_Prevent_Video_Preload.user.js`](#xenforo_prevent_video_preloaduserjs)
    * [`XenForo_Toggle_Categories.user.js`](#xenforo_toggle_categoriesuserjs)
  * [Miscellaneous](#miscellaneous)
    * [`EventHandler.user.js`](#eventhandleruserjs-more)
    * [`Facebook_Content_Warning_Generator.user.js`](#facebook_content_warning_generatoruserjs-more)
    * [`Facebook_Page_Moderation_Tools.user.js`](#facebook_page_moderation_toolsuserjs-more)
    * [`Freeze_All_GIFs.user.js`](#freeze_all_gifsuserjs)
    * [`GlobalVariableConstructor.user.js`](#globalvariableconstructoruserjs-more)
    * [`MakazeScriptOptions_Menu.user.js`](#makazescriptoptions_menuuserjs-more)
    * [`OMF_QT_Gen.user.js`](#omf_qt_genuserjs)
    * [`SF_Change_FE_in_Miniprofiles.user.js`](#sf_change_fe_in_miniprofilesuserjs)
    * [`SF_Mafia_Disable_Post_Editing.user.js`](#sf_mafia_disable_post_editinguserjs)
    * [`Serenes_Forest_Mafia_Votal_Generator.user.js`](#sernes_forest_mafia_votal_generatoruserjs)
    * [`Serenes_Forest_Thread_Extractor.user.js`](#sernes_forest_thread_extractoruserjs)
    * [`Tumblr_Custom_Buttons.user.js`](#tumblr_custom_buttonsuserjs)
    * [`Tumblr_Custom_Shortcuts.user.js`](#tumblr_custom_shortcutsuserjs)
    * [`Tumblr_Inline_Queue_Button.user.js`](#tumblr_inline_queue_buttonuserjs)

## IP.Board

#### `IP.Board_Auto-Save_Posts.user.js` [More](../../wiki/IP.Board:-Post-Auto-Saving-&-Management "Wiki")  
**Name**: IP.Board Post Auto-Saving + Management  
**Description**: Save and manage post drafts for IP.Board forums.  

#### `IP.Board_Automatic_Notifications.user.js`
**Name**: IP.Board - Automatic Notifications  
**Description**: Automatically loads new Forum and Messages notifications without refreshing the page.  

#### `IP.Board_Custom_Avatars.user.js`  
**Name**: IP.Board - Custom Avatars  
**Description**: AAllows users to customise or remove avatars on their display on a user-by-user basis.  

#### `IP.Board_Forum_Cleanup.user.js`  
**Name**: IP.Board - Forum Cleanup  
**Description**: Cleans up the IP.Board interface.  

#### `IP.Board_Hide_Gender_in_Miniprofies.user.js`  
**Name**: IP.Board - Hide Gender in Miniprofiles  
**Description**: IP.Board - Hide Gender in Miniprofiles  

#### `IP.Board_Hide_Ignored_Post_Notices.user.js`  
**Name**: IP.Board - Hide Ignored Post Notices
**Description**: Hides notices that a post has been ignored in threads and thread summaries.

#### `IP.Board_Isolate_Posts_by_User.user.js` [More](../../wiki/IP.Board:-Isolate-Posts-by-User "Wiki")  
**Name**: IP.Board - Isolate Posts by User  
**Description**: Adds links to 'Who posted in' lists and posts that generate all posts by that user in the thread.  

#### `IP.Board_Lockpick_Quotes.user.js`  
**Name**: IP.Board - Lockpick Quotes  
**Description**: Enables quoting posts from locked threads as MultiQuotes.  

#### `IP.Board_Member_Nicknames.user.js` [More](../../wiki/IP.Board:-Member-Nicknames "Wiki")  
**Name**: IP.Board - Member Nicknames  
**Description**: Adds an optional customized Nickname field to the profiles of members of your choice.  

#### `IP.Board_Navigation_Shortcuts.user.js` [More](../../wiki/IP.Board:-Navigation-Shortcuts "Wiki")  
**Name**: IP.Board - Navigation Shortcuts  
**Description**: Adds keyboard navigation shortcuts to XenForo.  

#### `IP.Board_Plaintext_BBCode.user.js` [More](../../wiki/IP.Board:-Plaintext-BBCode "Wiki")  
**Name**: IP.Board - Plaintext BBCode  
**Description**: Adds BBCode button support to Plaintext editor mode.  

#### `IP.Board_Post_Loss_Prevention.user.js`
**Name**: IP.Board Post Loss Prevention  
**Description**: Force the browser to ask you before leaving a page with an unfinished post.  

#### `IP.Board_Post_Style.user.js` [More](../../wiki/IP.Board:-Post-Style "Wiki")  
**Name**: IP.Board - Post Style  
**Description**: Adds options to apply a predefined style to posts in a variety of ways.  

#### `IP.Board_Prevent_Video_Preload.user.js`  
**Name**: IP.Board - Prevent Video Preload  
**Description**: Prevents the browser from pre-downloading embedded videos.  

#### `IP.Board_Quote_Search_Results.user.js`  
**Name**: IP.Board - Quote Search Results 
**Description**: Enables quoting posts from Search Results as MultiQuotes.  

#### `IP.Board_True_Ignore.user.js`  
**Name**: IP.Board - True Ignore  
**Description**: Also blocks users' quotes and post previews when you have them on ignore. 

## IP.Chat

#### `IP.Chat-Specific_Theme.user.js`  
**Name**: IP.Chat-Specific Theme  
**Description**: IP.Chat-Specific Theme  

#### `IP.Chat_Auto-Resizing_Popup.user.js`  
**Name**: IP.Chat - Auto-Resizing Popup  
**Description**: Automatically resizes the chat container to fill the window when in pop-up mode.  

#### `IP.Chat_Convert_Smilies_to_Text.user.js` [More](../../wiki/IP.Chat:-Convert-Smilies-to-Text "Wiki")  
**Name**: IP.Chat - Convert Smilies to Text  
**Description**: Like it says on the tin.  

#### `IP.Chat_Extension.user.js` [More](../../wiki/IP.Chat:-Extended-History-&-Concise-Format "Wiki")  
**Name**: IP.Chat Extended History + Concise Format  
**Description**: Extend IP.Chat history and make messages concise (optional).  

#### `IP.Chat_Ignore.user.js` [More](../../wiki/IP.Chat:-Ignore "Wiki")  
**Name**: IP.Chat Ignore  
**Description**: Allows you to ignore chat messages from specific users.  

#### `IP.Chat_Kick_Notice.user.js`  
**Name**: IP.Chat Kick Notice  
**Description**: Adds [KICKED] to the page title when you have been kicked.  

#### `IP.Chat_Logs.user.js` [More](../../wiki/IP.Chat:-Logs "Wiki")  
**Name**: IP.Chat Logs  
**Description**: Keep and manage IRC-like logs for IP.Chat clients.  

#### `IP.Chat_Nickname_Users.user.js` [More](../../wiki/IP.Chat:-Nickname-Users "Wiki")  
**Name**: IP.Chat - Nickname Users  
**Description**: Add secondary nicknames for users - shown only in IP.Chat.  

#### `IP.Chat_Pings.user.js` [More](../../wiki/IP.Chat:-Pings-&-Highlights "Wiki")  
**Name**: IP.Chat Pings + Highlights   
**Description**: Pings you when specified words are said in the chat.  

#### `dice_concise.user.js` [More](../../wiki/dice_concise-for-IP.Chat "Wiki")  
**Name**: dice_concise for IP.Chat  
**Description**: A concise dice simulator for IP.Chat.  

## XenForo

#### `XenForo_Alerts_in_Page_Title.user.js`  
**Name**: XenForo - Alerts in Page Title  
**Description**: Shows the number of alerts in the page title.  

#### `XenForo_Auto-applying_Macros.user.js` [More](../../wiki/XenForo:-Auto-applying-Macros "Wiki")  
**Name**: XenForo - Auto-applying Macros  
**Description**: Adds an option to automatically apply XenForo Macros.  

#### `XenForo_Auto-refresh_Users_Viewing_Thread.user.js`  
**Name**: XenForo - Auto-refresh Users Viewing Thread  
**Description**: Refreshes the 'Users Viewing Thread' field every 10 seconds.  

#### `XenForo_Avatar_Preview.user.js` [More](../../wiki/XenForo:-Avatar-Preview "Wiki")  
**Name**: XenForo - Avatar Preview  
**Description**: Generates a post preview for an avatar.  

#### `XenForo_Block_Signatures.user.js` [More](../../wiki/XenForo:-Hide-Signatures-for-Certain-Users "Wiki")  
**Name**: XenForo - Hide Signatures for Certain Users  
**Description**: Adds an option to hide users' signatures on XenForo.  

#### `XenForo_Expanded_Search_Results.user.js` [More](../../wiki/XenForo:-Expanded-Search-Results "Wiki")  
**Name**: XenForo - Expanded Search Results  
**Description**: Shows expanded posts in search results instead of snippets.  

#### `XenForo_Hide_Gender_in_Miniprofiles.user.js`  
**Name**: XenForo - Hide Gender in Miniprofiles  
**Description**: Like it says on the tin.  

#### `XenForo_Isolate_Posts_by_User.user.js` [More](../../wiki/XenForo:-Isolate-Posts-by-User "Wiki")  
**Name**: XenForo - Isolate Posts by User  
**Description**: Adds a button to the Mini-profilw to display all posts by that user in the thread.  

#### `XenForo_Lockpick_Quotes.user.js`  
**Name**: XenForo - Lockpick Quotes  
**Description**: Enables quoting posts from locked threads as MultiQuotes.  

#### `XenForo_Member_Nicknames.user.js` [More](../../wiki/XenForo:-Member-Nicknames "Wiki")  
**Name**: XenForo - Member Nicknames  
**Description**: Adds an optional customized Nickname field to the profiles of members of your choice.  

#### `XenForo_Message_Archiver.user.js` [More](../../wiki/XenForo:-Message-Archiver "Wiki")  
**Name**: XenForo - Message Archiver  
**Description**: Converts XenForo thread and conversation messages into text format for easy archiving.  

#### `XenForo_Navigation_Shortcuts.user.js` [More](../../wiki/XenForo:-Navigation-Shortcuts "Wiki")  
**Name**: XenForo - Navigation Shortcuts  
**Description**: Adds keyboard navigation shortcuts to XenForo.  

#### `XenForo_Plaintext_BBCode.user.js` [More](../../wiki/XenForo:-Plaintext-BBCode "Wiki")  
**Name**: XenForo - Plaintext BBCode  
**Description**: Adds BBCode buttons to Plaintext Mode on XenForo.  

#### `XenForo_Post_Style.user.js` [More](../../wiki/XenForo:-Post-Style "Wiki")  
**Name**: XenForo - Post Style  
**Description**: Adds options to apply a predefined style to posts in a variety of ways.  

#### `XenForo_Prevent_Video_Preload.user.js`  
**Name**: XenForo - Prevent Video Preload  
**Description**: Prevents the browser from pre-downloading embedded videos.  

#### `XenForo_Toggle_Categories.user.js`  
**Name**: XenForo - Toggle Categories Categories  
**Description**: Toggle the visibility of categories by clicking the title bar.  

Miscellaneous
===============

#### `EventHandler.user.js` [More](../../wiki/Miscellaneous:-EventHandler:-Manage-JavaScript-Events "Wiki")  
**Name**: EventHandler - Manage JavaScript Events  
**Description**: Constructor/library to add, search through and remove event listeners. Supports adding and removing multiple types of events simultaneously.  

#### `Facebook_Content_Warning_Generator.user.js` [More](../../wiki/Miscellaneous:-Facebook-Content-Warning-Generator "Wiki")  
**Name**: Facebook - Content Warning Generator  
**Description**: Adds a content warning generator dropdown for posts.  

#### `Facebook_Page_Moderation_Tools.user.js` [More](../../wiki/Miscellaneous:-Facebook-Page-Moderation-Tools "Wiki")  
**Name**: Facebook - Page Moderation Tools  
**Description**: Adds an automated method for banning members from a page even before they like or comment.  

#### `Freeze_All_GIFs.user.js`  
**Name**: Freeze All GIFs  
**Description**: Freezes all animated GIFs on a page.  

#### `GlobalVariableConstructor.user.js` [More](../../wiki/Miscellaneous:-Access-Global-Variables-from-Userscripts "Wiki")  
**Name**: Access Global Variables from Userscripts  
**Description**: Constructor/library to read and set globals from the content/userscript scope. Works in Google Chrome.  

#### `MakazeScriptOptions_Menu.user.js` [More](../../wiki/Miscellaneous:-Makaze-Scripts-Options-Menu "Wiki")  
**Name**: Makaze Scripts Options Menu  
**Description**: Creates, edits and deletes options for my scripts.  

#### `OMF_QT_Gen.user.js`  
**Name**: OMF Question Time Generation  
**Description**: OMF Question Time Generation  

#### `SF_Change_FE_in_Miniprofiles.user.js`  
**Name**: Serenes Forest - Change 'Favorite Fire Emblem' to 'Favorite FE' in Miniprofiles  
**Description**: Like it says on the tin.  

#### `SF_Mafia_Disable_Post_Editing.user.js`  
**Name**: SF Mafia - Disable Post Editing  
**Description**: Disables the post editing button in the mafia subforum.  

#### `Serenes_Forest_Mafia_Votal_Generator.user.js`  
**Name**: Serenes Forest - Mafia Votal Generator  
**Description**: A feature-rich votal generator for Serenes Forest Mafia.  

#### `Serenes_Forest_Thread_Extractor.user.js`  
**Name**: Serenes Forest - Thread Extractor  
**Description**: Extracts threads as a sortable table.  

#### `Tumblr_Custom_Buttons.user.js`  
**Name**: Tumblr - Custom Buttons  
**Description**: Adds custom buttons to the Tumblr Editor.  

#### `Tumblr_Custom_Shortcuts.user.js`  
**Name**: Tumblr - Custom Shortcuts  
**Description**: Adds custom shortcuts to the Tumblr Editor.  

#### `Tumblr_Inline_Queue_Button.user.js`  
**Name**: Tumblr - Inline Queue Button  
**Description**: Adds a Queue button to avoid using the submission dropdown.  
