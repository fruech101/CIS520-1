To create the new alarm-mega test program we had to do this in the src/tests/threads folder

-create a file called alarm-mega.ck with the same code as alarm-multiple.ck replacing 7 with 70
-edit the file test.c, adding the line "    {"alarm-mega", test_alarm_mega}," to the test[] struct
-edit the file test.h, adding the line "extern test_func test_alarm_mega;" below alarm single
-edit the file Rubric.alarm, adding the line "4	alarm-mega"
-edit the file alarm-wait.c, adding the function test_alarm_mega, with the same code as the funtion test_alarm_multilple, replacing 7 with 70

