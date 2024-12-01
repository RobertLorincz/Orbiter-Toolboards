Changes v2.2.5

- Included CANCEL macro for user using the sensor macros instead of their own macros
- Pausing printer due to runnout detection increases printer timeout to 3600s - 1h (configurable by pause_timeout); timeout set back to default ten minutes after print resume.
- improved temperature restore behavior
- Filament automatic unload after runnout can be disabled by variable disable_runout_unload.
- corrected some minor bugs and spelling
- messages sent to console shows SO3: prefix
- corrected RGB led incorrect color status for some failure cases
