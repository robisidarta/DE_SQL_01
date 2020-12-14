# DE_SQL_01
select UserId, AVG(duration) as average from sessions
group by UserId
