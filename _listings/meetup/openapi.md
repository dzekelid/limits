swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname/events/:id/attendance:
    get:
      summary: Attendance
      description: Lists attendance records for Meetup events. Limited for use by
        administrative members.
      operationId: events
      x-api-path-slug: urlnameeventsidattendance-get
      parameters:
      - in: query
        name: filter
        description: A named filter to apply to the attendance list
        type: string
      - in: query
        name: member
        description: Raw text used to search for member by name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Attendance
    post:
      summary: Attendance Taking
      description: Takes member attendance for an event. Limited for use by administrative
        members.
      operationId: events
      x-api-path-slug: urlnameeventsidattendance-post
      parameters:
      - in: query
        name: guests
        description: The number of guests accompanying member
        type: string
      - in: query
        name: headcount
        description: Sets the overall headcount for the event
        type: string
      - in: query
        name: member
        description: A comma-delimited list of valid ids associated with members RSVPd
          to the event
        type: string
      - in: query
        name: status
        description: An attendance status for the provided members
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Attendance
  /:urlname/topics:
    post:
      summary: Group Topics Add
      description: Associates topics with a given Meetup group. Limited to organizers
        of the group. OAuth authenticated requests require an additional [group_edit](/meetup_api/auth/#oauth2-scopes)
        permission.
      operationId: groups
      x-api-path-slug: urlnametopics-post
      parameters:
      - in: query
        name: topic_id
        description: Comma-delimited list of topic ids to associate with group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
    delete:
      summary: Group Topics Remove
      description: Disassociates topics with a given Meetup group. Limited to organizers
        of the group. OAuth authenticated requests require an additional [group_edit](/meetup_api/auth/#oauth2-scopes)
        permission.
      operationId: groups
      x-api-path-slug: urlnametopics-delete
      parameters:
      - in: query
        name: topic_id
        description: Comma-delimited list of topic ids to disassociate with group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos