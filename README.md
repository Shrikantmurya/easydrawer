# Easy Drawer

```
  @override
  Widget build(BuildContext context) {
     List admindrawerMenus = [
        {"title": "All Users", "icon": Icons.person, "subMenu": true, "submenuData": [
        {"title": "Admin", "event":(){}, "supersubmenu": false}, 
        {"title": "Managers", "event":(){ }, "supersubmenu": false},
        {"title": "Counselors", "event":(){}, "supersubmenu": false}, 
        {"title": "Agents", "event":(){ }, "supersubmenu": false },
        {"title": "Admission", "event":(){ }, "supersubmenu": false }, 
        {"title": "Filling", "event":(){ }, "supersubmenu": false}, 
        {"title": "Reception", "event":(){ }, "supersubmenu": false},
        ],},
     
     {"title": "Leads", "icon": Icons.leaderboard, "subMenu": true, "submenuData": [
      {"title": "All Leads", "event":(){ }, "supersubmenu": false},
      {"title": "All Clients", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
      {"title": "Add Leads", "event":(){ print('submenu 2');},  "supersubmenu": false},
      {"title": "Assign Leads", "supersubmenu": true, "supersubData": [
        {"title": "Via LB Leads", "event":(){ print('supersubmenu 1');}},
        {"title": "Re-allocation Requests", "event":(){ print('supersubmenu 2');}},
        {"title": "Bulk Leads Delete", "event":(){ print('supersubmenu 2');}, }
      ],},
      ],},

    {"title": "Auto Dial Lead", "icon": Icons.autorenew, "subMenu": false, "event": (){ print('menu 1');},}, 

    {"title": "Masters", "icon": Icons.menu, "subMenu": true, "submenuData": [
      {"title": "Upload Institute & Courses", "event":(){ print('submenu 1');}, "supersubmenu": false},
      {"title": "Course Content", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
      {"title": "Config SMTP", "event":(){ print('submenu 2');},  "supersubmenu": false},
      {"title": "SMS Template", "event":(){ print('submenu 2');},  "supersubmenu": false},
      {"title": "Config SMTP", "event":(){ print('submenu 2');},  "supersubmenu": false},
      {"title": "Email Template", "supersubmenu": true, "supersubData": [
      {"title": "IELTS", "event":(){ print('supersubmenu 1');}},
        {"title": "Campaigns", "event":(){ print('supersubmenu 2');}},
        {"title": "College Agent", "event":(){ print('supersubmenu 2');}},
        {"title": "Country", "event":(){ print('supersubmenu 2');}},
        {"title": "Intake", "event":(){ print('supersubmenu 2');}},
        {"title": "City", "event":(){ print('supersubmenu 2');}},
        {"title": "Campuses", "event":(){ print('supersubmenu 2');}},
        {"title": "Qualification", "event":(){ print('supersubmenu 2');}},
        {"title": "Stream", "event":(){ print('supersubmenu 2');}},
        {"title": "Institute", "event":(){ print('supersubmenu 2');}},
        {"title": "Course", "event":(){ print('supersubmenu 2');}},
        {"title": "Branch", "event":(){ print('supersubmenu 2');}},
        {"title": "Status", "event":(){ print('supersubmenu 2');}},
        {"title": "Sub Status", "event":(){ print('supersubmenu 2');}},
        {"title": "Source", "event":(){ print('supersubmenu 2');}},
        {"title": "Admision Docs Checklist", "event":(){ print('supersubmenu 2');}},
        {"title": "Filing Docs Checklist", "event":(){ print('supersubmenu 2');}},
        {"title": "Registration Plans", "event":(){ print('supersubmenu 2');}},
        {"title": "Expense Types", "event":(){ print('supersubmenu 2');}},
        {"title": "Bank Details", "event":(){ print('supersubmenu 2');}},
        {"title": "IP Address Access", "event":(){ print('supersubmenu 2');}},
        {"title": "Access Grant", "event":(){ print('supersubmenu 2');}},
        {"title": "Setting", "event":(){ print('supersubmenu 2');}},
      ],},
      ],},

      {"title": "Followups", "icon": Icons.follow_the_signs, "subMenu": true, "submenuData": [
        {"title": "Today Followups", "event":(){ print('submenu 1');}, "supersubmenu": false},
        {"title": "Pending Followups", "event":(){ print('submenu 2');}, "supersubmenu": false},
        {"title": "Today's Done Followups", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        ],},
      {"title": "Assign Admissions", "icon": Icons.assignment_ind, "subMenu": false, "event": (){ print('menu 1');},}, 
      {"title": "Payment Status", "icon": Icons.payment, "subMenu": false, "event": (){ print('menu 1');},}, 
      {"title": "Expected Walkin", "icon": Icons.thumb_up_alt, "subMenu": false, "event": (){ print('menu 1');},}, 
      {"title": "Expected Sale", "icon": Icons.bar_chart, "subMenu": false, "event": (){ print('menu 1');},}, 

      {"title": "SOP", "icon": Icons.insert_drive_file, "subMenu": true, "submenuData": [
        {"title": "Buy SOP", "event":(){ print('submenu 1');}, "supersubmenu": false},
        ],},
      
      {"title": "Financial", "icon": Icons.wallet, "subMenu": true, "submenuData": [
        {"title": "Expenses", "event":(){ print('submenu 1');}, "supersubmenu": false},
        {"title": "Cash Deposit/Transfer", "event":(){ print('submenu 2');}, "supersubmenu": false},
        {"title": "Cash Flow Report", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        ],},

      {"title": "All Reports", "icon": Icons.list_alt, "subMenu": true, "submenuData": [
        {"title": "Overall Performense", "event":(){ print('submenu 1');}, "supersubmenu": false},
        {"title": "Campaign Status Report", "event":(){ print('submenu 2');}, "supersubmenu": false},
        {"title": "Branch/Colleges Admissions", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        ],},  

        {"title": "Add Dropout", "icon": Icons.person_add_disabled, "subMenu": false, "event": (){ print('menu 1');},}, 
        {"title": "Tips & Messages", "icon": Icons.tips_and_updates, "subMenu": false, "event": (){ print('menu 1');},}, 

        {"title": "Country Process", "icon": Icons.language, "subMenu": true, "submenuData": [
        {"title": "Canada", "event":(){ print('submenu 1');}, "supersubmenu": false},
        {"title": "NWZ &AUS", "event":(){ print('submenu 2');}, "supersubmenu": false},
        {"title": "Sample Documents", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        ],},  

        {"title": "Support", "icon": Icons.help, "subMenu": false, "event": (){ print('menu 1');},}, 
       {"title": "Guides", "icon": Icons.label, "subMenu": true, "submenuData": [
        {"title": "Admin", "event":(){ print('submenu 1');}, "supersubmenu": false},
        {"title": "Manager", "event":(){ print('submenu 2');}, "supersubmenu": false},
        {"title": "Counselor", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        {"title": "Agent", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        {"title": "Admission", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        {"title": "Filling", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        {"title": "Reception", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        {"title": "GIC Guide", "event":(){ print('submenu 2');}, "supersubmenu": false}, 
        ],},  
        {"title": "Appointments", "icon": Icons.event_note, "subMenu": false, "event": (){ print('menu 1');},}, 
        {"title": "Fintech Services", "icon": Icons.label, "subMenu": true, "submenuData": [
          {"title": "Request Fintech Services", "event":(){ print('submenu 1');}, "supersubmenu": false},
          {"title": "Applied Fintech Services", "event":(){ print('submenu 2');}, "supersubmenu": false},
        ],},  
        {"title": "AI SOP Generator", "icon": Icons.edit_road, "subMenu": false, "event": (){ print('menu 1');},}, 
        {"title": "Course Finder", "icon": Icons.search, "subMenu": false, "event": (){ print('menu 1');},}, 
       
    ];
  
    return MaterialApp(
      home: Scaffold(
       
         drawer: Drawer(
          child: CommonDrawer(draweList: admindrawerMenus,  text: 'Lorem Ipsum', imgUrl: 'assets/images/dummyprofile.png', color:AppColor.darkBlueColor, colIcn: Icons.add, expIcn: Icons.minimize_outlined)
        ),
        body: Text('Eassy Drawer'),
      ),
    );
  }
```

