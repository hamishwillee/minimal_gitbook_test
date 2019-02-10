# Doc 1

Some text. 

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```

Test

```mermaid
sequenceDiagram;
    participant GCS
    participant Drone
    GCS->>Drone: MAV_CMD_REQUEST_PROTOCOL_VERSION
    GCS->>GCS: Start timeout
    Drone->>GCS: PROTOCOL_VERSION in MAVLink 2 framing
    GCS->>Drone: If ACK: Switches to MAVLink 2
    Drone->>GCS: Switches to MAVLink 2 on receive
```


kdlfjaljas

```mermaid
sequenceDiagram;
    participant GCS
    participant Drone
    Note right of GCS: Open file
    GCS->>Drone:  OpenFileRO( data[0]=path, size=len(path) )
    Drone-->>GCS: ACK( session, size=len(file) )
    Note right of GCS: Read file in chunks<br>(call at offset)
    GCS->>Drone:  ReadFile(session, size, offset)
    Drone-->>GCS: ACK(session, size=len(buffer), data[0]=buffer)
    Note right of GCS: Continue until NAK<br> with EOF
    Drone-->>GCS: NAK(session, size=1, data=EOF)
    Note right of GCS: Close session
    GCS->>Drone:  TerminateSession(session)
    Drone-->>GCS: ACK()
```

## 2nd level heading

Some text. 

# A 3rd level heading

Some text. 

## Another Second level heading

Some text. 

## Asserts

> **Tip** This is a tip.

<span></span>
> **Note** This is a note.

<span></span>
> **Warning** This is a warning.

<span></span>
> **Todo** This is a todo.

This is a new tag test.