1. Measurable Validation Criteria (2 Marks)
Module	Stakeholder Expectation	Validation Criteria (Measurable)
Student Login	Secure and fast login	Login success rate ≥ 99%, response time ≤ 2 sec, MFA enabled
Assignment Submission	Reliable uploads	File upload success ≥ 98%, max size validation, virus scan pass
Attendance Tracking	Accurate records	Attendance accuracy ≥ 99%, timestamp integrity maintained
Faculty Dashboard	Real-time insights	Data refresh latency ≤ 3 sec, role-based access enforced
Activity Logging	Traceability	100% critical actions logged, logs immutable, timestamped

2. Structured Validation Checklist (3 Marks)

ID	Module	Validation Item	Criteria	Test Method	Expected Result	Status	Remarks
VC-01	Login	Input validation	No SQL/XSS allowed	Pen test	Input sanitized	YES	
VC-02	Login	Authentication	MFA enforced	Functional test	MFA required	YES	
VC-03	Assignment	File upload	File type restriction	Upload test	Only PDF/DOC allowed	YES	
VC-04	Attendance	Timestamp	Accurate logging	System test	Correct time recorded	YES	
VC-05	Dashboard	Role access	RBAC enforced	Access test	Unauthorized blocked	YES	
VC-06	Logging	Audit logs	All actions logged	Log review	Complete logs	YES	
