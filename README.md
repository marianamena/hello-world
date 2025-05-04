check events and waits in oracle:
SELECT p3, count(*) 
  FROM v$session_wait 
  WHERE event='buffer busy wait'
;
