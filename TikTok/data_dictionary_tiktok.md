[Link to Course 3 Tableau template](https://public.tableau.com/app/profile/grow.with.google/viz/TikTokEndofCourseProject-Course3/Story1#1)

[Course 3 Tableau Instructions](https://docs.google.com/document/d/1p-d4-9QrcJZWky2tF9CK68X-22RIbXM-Fu76wxD3HHI/template/preview?resourcekey=0-L7ntrywzdZC0kbx7F59UTg)

# Data Dictionary

This project uses a dataset called `tiktok_dataset.csv`. It contains synthetic data created for this project in partnership with TikTok.

### Dataset Overview:
- **Rows:** 19,383 (each row represents a different published TikTok video in which a claim/opinion has been made)
- **Columns:** 12

### Columns and Descriptions:

| **Column Name**            | **Type**  | **Description**                                                                                                                   |
|-----------------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------|
| **#**                      | `int`     | TikTok assigned number for video with claim/opinion.                                                                              |
| **claim_status**            | `obj`     | Whether the published video has been identified as an “opinion” or a “claim.”                                                    |
|                             |           | - **Opinion:** An individual’s or group’s personal belief or thought.                                                            |
|                             |           | - **Claim:** Information that is either unsourced or from an unverified source.                                                  |
| **video_id**                | `int`     | Random identifying number assigned to video upon publication on TikTok.                                                          |
| **video_duration_sec**      | `int`     | How long the published video is measured in seconds.                                                                              |
| **video_transcription_text**| `obj`     | Transcribed text of the words spoken in the published video.                                                                      |
| **verified_status**         | `obj`     | Indicates the status of the TikTok user who published the video in terms of their verification:                                   |
|                             |           | - **Verified**                                                                                                                   |
|                             |           | - **Not verified**                                                                                                               |
| **author_ban_status**       | `obj`     | Indicates the status of the TikTok user who published the video in terms of their permissions:                                    |
|                             |           | - **Active**                                                                                                                     |
|                             |           | - **Under scrutiny**                                                                                                             |
|                             |           | - **Banned**                                                                                                                     |
| **video_view_count**        | `float`   | The total number of times the published video has been viewed.                                                                    |
| **video_like_count**        | `float`   | The total number of times the published video has been liked by other users.                                                     |
| **video_share_count**       | `float`   | The total number of times the published video has been shared by other users.                                                    |
| **video_download_count**    | `float`   | The total number of times the published video has been downloaded by other users.                                                |
| **video_comment_count**     | `float`   | The total number of comments on the published video.                                                                              |