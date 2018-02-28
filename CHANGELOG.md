## 1.1.16
- Fixed not being able to read multiple gzipped file streams in a single file issue

## 1.1.15
- Fixed throttle error

## 1.1.14
- Fixed compilation error

## 1.1.13
- Added support for processing plain text json by removing whitespaces first

## 1.1.12
- Updated codec use based on content type and resolved compilation error

## 1.1.11
- Added content encoding and content type to events

## 1.1.10
- Added throttle capability to slow down processing based on file size

## 1.1.9
- Added metadata keys to the event

## 1.1.8
- Fixed event type metadata

## 1.1.7
- Added event type metadata to know when file is processed, and generate event with SQS message details

## 1.1.6
- Added skip-delete parameter and receipt handle

## 1.1.0
- Logstash 5 compatibility

## 1.0.3
- added some metadata to the event (bucket and object name as commited by joshuaspence)
- also try to unzip files ending with ".gz" (ALB logs are zipped but not marked with proper Content-Encoding)

## 1.0.2
- fix for broken UTF-8 (so we won't lose a whole s3 log file because of a single invalid line, ruby's split will die on those)

## 1.0.1
- same (because of screwed up rubygems.org release)

## 1.0.0
- Initial Release
