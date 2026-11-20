<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pro Staff & Site Management System</title>
    <style>
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --secondary: #0f172a;
            --bg-light: #f1f5f9;
            --white: #ffffff;
            --text-dark: #1e293b;
            --text-muted: #64748b;
            --success: #10b981;
            --danger: #ef4444;
            --warning: #f59e0b;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
            display: flex;
            min-height: 100vh;
        }

        /* Sidebar */
        .sidebar {
            width: 260px;
            background-color: var(--secondary);
            color: var(--white);
            display: flex;
            flex-direction: column;
            padding: 20px 0;
            position: fixed;
            height: 100vh;
            overflow-y: auto;
        }

        .brand {
            padding: 0 25px 20px;
            border-bottom: 1px solid #334155;
            margin-bottom: 20px;
        }

        .brand h2 {
            font-size: 20px;
            color: #38bdf8;
        }

        .brand p {
            font-size: 12px;
            color: #94a3b8;
        }

        .nav-item {
            padding: 14px 25px;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 12px;
            color: #cbd5e1;
            transition: 0.2s;
            font-size: 15px;
        }

        .nav-item:hover, .nav-item.active {
            background-color: var(--primary);
            color: var(--white);
            border-left: 4px solid #38bdf8;
        }

        /* Main Content */
        .main-content {
            margin-left: 260px;
            flex: 1;
            padding: 30px;
            width: calc(100% - 260px);
        }

        .topbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: var(--white);
            padding: 15px 25px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.04);
            margin-bottom: 25px;
        }

        .role-switch {
            display: flex;
            gap: 10px;
            align-items: center;
        }

        .role-btn {
            padding: 8px 16px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-weight: 600;
            font-size: 13px;
        }

        .role-btn.admin-active { background: var(--primary); color: white; }
        .role-btn.staff-active { background: var(--success); color: white; }
        .role-btn.inactive { background: #e2e8f0; color: var(--text-dark); }

        /* Stats Cards */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .stat-card {
            background: var(--white);
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.04);
            border-left: 5px solid var(--primary);
        }

        .stat-card.green { border-left-color: var(--success); }
        .stat-card.orange { border-left-color: var(--warning); }
        .stat-card.red { border-left-color: var(--danger); }

        .stat-card h4 {
            font-size: 13px;
            color: var(--text-muted);
            text-transform: uppercase;
            margin-bottom: 8px;
        }

        .stat-card .value {
            font-size: 26px;
            font-weight: 700;
        }

        /* Sections & Forms */
        .page-section {
            display: none;
            background: var(--white);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.04);
        }

        .page-section.active {
            display: block;
        }

        .section-title {
            font-size: 18px;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 1px solid #e2e8f0;
            color: var(--secondary);
        }

        .form-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            font-size: 13px;
            font-weight: 600;
            margin-bottom: 6px;
            color: var(--text-dark);
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 10px 12px;
            border: 1px solid #cbd5e1;
            border-radius: 8px;
            font-size: 14px;
            outline: none;
        }

        .form-group input:focus, .form-group select:focus {
            border-color: var(--primary);
        }

        .btn-primary {
            background: var(--primary);
            color: white;
            border: none;
            padding: 11px 22px;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            transition: 0.2s;
        }

        .btn-primary:hover {
            background: var(--primary-dark);
        }

        .btn-secondary {
            background: #64748b;
            color: white;
            border: none;
            padding: 11px 18px;
            border-radius: 8px;
            font-weight: 600;
            cursor: pointer;
            margin-left: 8px;
        }

        /* Tables */
        .table-responsive {
            overflow-x: auto;
            margin-top: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 14px;
        }

        th, td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #e2e8f0;
        }

        th {
            background-color: #f8fafc;
            color: var(--text-muted);
            font-weight: 600;
        }

        .badge {
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        .badge-present { background: #dcfce7; color: #166534; }
        .badge-absent { background: #fee2e2; color: #991b1b; }
        .badge-half { background: #fef3c7; color: #92400e; }

        .btn-edit {
            background: #e0f2fe;
            color: #0369a1;
            border: none;
            padding: 5px 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 12px;
            font-weight: 600;
            margin-right: 6px;
        }

        .btn-del {
            background: #fee2e2;
            color: #dc2626;
            border: none;
            padding: 5px 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 12px;
            font-weight: 600;
        }

        /* Responsive Mobile */
        @media (max-width: 768px) {
            body { flex-direction: column; }
            .sidebar { width: 100%; height: auto; position: relative; flex-direction: row; overflow-x: auto; padding: 10px; }
            .brand { display: none; }
            .nav-item { padding: 10px 15px; white-space: nowrap; border-left: none !important; border-radius: 6px; }
            .main-content { margin-left: 0; width: 100%; padding: 15px; }
        }
    </style>
</head>
<body>

    <!-- Sidebar Navigation -->
    <div class="sidebar">
        <div class="brand">
            <h2>WorkForce Pro</h2>
            <p>Staff & Site Management</p>
        </div>
        <div class="nav-item active" onclick="showSection('dashboard', this)">📊 Dashboard</div>
        <div class="nav-item admin-only" onclick="showSection('add-staff', this)">👥 Staff & Edit</div>
        <div class="nav-item" onclick="showSection('attendance-site', this)">📍 Attendance & Site</div>
        <div class="nav-item" onclick="showSection('ot-management', this)">⏱️ OT Details</div>
        <div class="nav-item" onclick="showSection('payments', this)">💸 Advance & Daily Pay</div>
        <div class="nav-item admin-only" onclick="showSection('salary-report', this)">💰 Salary Summary</div>
    </div>

    <!-- Main Content -->
    <div class="main-content">
        <!-- Topbar -->
        <div class="topbar">
            <div>
                <h3 id="page-heading">Dashboard Overview</h3>
                <small style="color: var(--text-muted);" id="current-date-display"></small>
            </div>
            <div class="role-switch">
                <span style="font-size: 13px; font-weight: 600;">Mode:</span>
                <button id="btn-role-admin" class="role-btn admin-active" onclick="setRole('admin')">Admin</button>
                <button id="btn-role-staff" class="role-btn inactive" onclick="setRole('staff')">Staff</button>
            </div>
        </div>

        <!-- 1. DASHBOARD SECTION -->
        <div id="dashboard" class="page-section active">
            <div class="stats-grid">
                <div class="stat-card">
                    <h4>Total Staff (ആകെ സ്റ്റാഫുകൾ)</h4>
                    <div class="value" id="stat-total-staff">0</div>
                </div>
                <div class="stat-card green">
                    <h4>Today's Attendance (ഇന്നത്തെ ഹാജർ)</h4>
                    <div class="value" id="stat-today-present">0</div>
                </div>
                <div class="stat-card orange">
                    <h4>Total Advance / Paid (നൽകിയ തുക)</h4>
                    <div class="value" id="stat-total-paid">₹0</div>
                </div>
                <div class="stat-card red">
                    <h4>Net Balance Payable (നൽകാനുള്ള ബാക്കി)</h4>
                    <div class="value" id="stat-net-balance">₹0</div>
                </div>
            </div>

            <h3 class="section-title">Recent Site & Attendance Logs</h3>
            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Date</th>
                            <th>Staff Name</th>
                            <th>Work Site</th>
                            <th>Status</th>
                            <th>Added By</th>
                        </tr>
                    </thead>
                    <tbody id="dashboard-recent-table"></tbody>
                </table>
            </div>
        </div>

        <!-- 2. ADD & EDIT STAFF SECTION -->
        <div id="add-staff" class="page-section">
            <h3 class="section-title" id="staff-form-title">Add New Staff (പുതിയ സ്റ്റാഫിനെ ചേർക്കുക)</h3>
            <form onsubmit="saveStaff(event)" id="staff-form">
                <input type="hidden" id="edit-staff-id">
                <div class="form-grid">
                    <div class="form-group">
                        <label>Staff Name (പേര്)*</label>
                        <input type="text" id="staff-name" required placeholder="ഉദാ: അരുൺ കുമാർ">
                    </div>
                    <div class="form-group">
                        <label>Phone Number (ഫോൺ)*</label>
                        <input type="tel" id="staff-phone" required placeholder="ഉദാ: 9876543210">
                    </div>
                    <div class="form-group">
                        <label>Designation / Role (തസ്തിക)*</label>
                        <input type="text" id="staff-role" required placeholder="ഉദാ: Technician / Helper">
                    </div>
                    <div class="form-group">
                        <label>Daily Wage / Salary (ദിവസക്കൂലി ₹)*</label>
                        <input type="number" id="staff-wage" required placeholder="ഉദാ: 850">
                    </div>
                </div>
                <button type="submit" class="btn-primary" id="staff-submit-btn">+ Save Staff</button>
                <button type="button" class="btn-secondary" id="staff-cancel-btn" style="display:none;" onclick="cancelStaffEdit()">Cancel Edit</button>
            </form>

            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Phone</th>
                            <th>Role</th>
                            <th>Daily Wage</th>
                            <th>Actions</th>
                        </tr>
                    </thead>
                    <tbody id="staff-list-table"></tbody>
                </table>
            </div>
        </div>

        <!-- 3. ATTENDANCE & WORK SITE DETAILS -->
        <div id="attendance-site" class="page-section">
            <h3 class="section-title">Attendance & Work Site Entry</h3>
            <form onsubmit="addAttendance(event)">
                <div class="form-grid">
                    <div class="form-group">
                        <label>Select Staff*</label>
                        <select id="att-staff" required></select>
                    </div>
                    <div class="form-group">
                        <label>Date*</label>
                        <input type="date" id="att-date" required>
                    </div>
                    <div class="form-group">
                        <label>Work Site Name / Location (സൈറ്റ് വിവരങ്ങൾ)*</label>
                        <input type="text" id="att-site" required placeholder="ഉദാ: Perinthalmanna Site / Town Project">
                    </div>
                    <div class="form-group">
                        <label>Attendance Status*</label>
                        <select id="att-status">
                            <option value="Present">Present (Full Day)</option>
                            <option value="Half Day">Half Day</option>
                            <option value="Absent">Absent</option>
                        </select>
                    </div>
                </div>
                <button type="submit" class="btn-primary">Submit Attendance & Site</button>
            </form>

            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Date</th>
                            <th>Staff</th>
                            <th>Work Site</th>
                            <th>Status</th>
                            <th>Wage Earned</th>
                            <th>By</th>
                            <th>Action</th>
                        </tr>
                    </thead>
                    <tbody id="attendance-table"></tbody>
                </table>
            </div>
        </div>

        <!-- 4. OT (OVERTIME) DETAILS -->
        <div id="ot-management" class="page-section">
            <h3 class="section-title">Overtime (OT) Entry</h3>
            <form onsubmit="addOT(event)">
                <div class="form-grid">
                    <div class="form-group">
                        <label>Select Staff*</label>
                        <select id="ot-staff" required></select>
                    </div>
                    <div class="form-group">
                        <label>Date*</label>
                        <input type="date" id="ot-date" required>
                    </div>
                    <div class="form-group">
                        <label>Work Site*</label>
                        <input type="text" id="ot-site" required placeholder="സൈറ്റിന്റെ പേര്">
                    </div>
                    <div class="form-group">
                        <label>OT Hours (മണിക്കൂർ)*</label>
                        <input type="number" step="0.5" id="ot-hours" required placeholder="ഉദാ: 2.5">
                    </div>
                    <div class="form-group">
                        <label>OT Amount (₹)*</label>
                        <input type="number" id="ot-amount" required placeholder="ഉദാ: 300">
                    </div>
                </div>
                <button type="submit" class="btn-primary">Save OT Details</button>
            </form>

            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Date</th>
                            <th>Staff</th>
                            <th>Work Site</th>
                            <th>Hours</th>
                            <th>OT Amount</th>
                            <th>Action</th>
                        </tr>
                    </thead>
                    <tbody id="ot-table"></tbody>
                </table>
            </div>
        </div>

        <!-- 5. ADVANCE & DAILY PAYMENT MANAGEMENT -->
        <div id="payments" class="page-section">
            <h3 class="section-title">Advance & Daily Payment Entry</h3>
            <form onsubmit="addPayment(event)">
                <div class="form-grid">
                    <div class="form-group">
                        <label>Select Staff*</label>
                        <select id="pay-staff" required></select>
                    </div>
                    <div class="form-group">
                        <label>Date*</label>
                        <input type="date" id="pay-date" required>
                    </div>
                    <div class="form-group">
                        <label>Payment Type*</label>
                        <select id="pay-type">
                            <option value="Advance">Advance Payment (അഡ്വാൻസ്)</option>
                            <option value="Daily Expense / Bata">Daily Payment / Bata (ദിവസച്ചെലവ്)</option>
                            <option value="Salary Settlement">Salary Settlement (ശമ്പളം നൽകിയത്)</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label>Amount (₹)*</label>
                        <input type="number" id="pay-amount" required placeholder="തുക നൽകുക">
                    </div>
                    <div class="form-group">
                        <label>Remarks / Note</label>
                        <input type="text" id="pay-note" placeholder="ഉദാ: GPay വഴി നൽകി">
                    </div>
                </div>
                <button type="submit" class="btn-primary">Record Payment</button>
            </form>

            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Date</th>
                            <th>Staff</th>
                            <th>Type</th>
                            <th>Amount</th>
                            <th>Note</th>
                            <th>Action</th>
                        </tr>
                    </thead>
                    <tbody id="payment-table"></tbody>
                </table>
            </div>
        </div>

        <!-- 6. SALARY MANAGEMENT & SUMMARY -->
        <div id="salary-report" class="page-section">
            <h3 class="section-title">Auto Salary & Balance Calculation (ശമ്പള കണക്കുകൾ)</h3>
            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Staff Name</th>
                            <th>Days Worked</th>
                            <th>Basic Wage (₹)</th>
                            <th>Total OT (₹)</th>
                            <th>Gross Salary (₹)</th>
                            <th>Advance / Paid (₹)</th>
                            <th>Balance Payable (₹)</th>
                        </tr>
                    </thead>
                    <tbody id="salary-summary-table"></tbody>
                </table>
            </div>
        </div>

    </div>

    <script>
        let currentRole = 'admin';

        let staffList = JSON.parse(localStorage.getItem('wf_staff')) || [];
        let attendanceList = JSON.parse(localStorage.getItem('wf_attendance')) || [];
        let otList = JSON.parse(localStorage.getItem('wf_ot')) || [];
        let paymentList = JSON.parse(localStorage.getItem('wf_payments')) || [];

        const today = new Date().toISOString().split('T')[0];
        document.getElementById('att-date').value = today;
        document.getElementById('ot-date').value = today;
        document.getElementById('pay-date').value = today;
        document.getElementById('current-date-display').innerText = new Date().toDateString();

        function showSection(sectionId, element) {
            document.querySelectorAll('.page-section').forEach(sec => sec.classList.remove('active'));
            document.querySelectorAll('.nav-item').forEach(nav => nav.classList.remove('active'));
            
            document.getElementById(sectionId).classList.add('active');
            if(element) element.classList.add('active');
            
            document.getElementById('page-heading').innerText = element ? element.innerText : 'Dashboard';
            updateAllUI();
        }

        function setRole(role) {
            currentRole = role;
            document.getElementById('btn-role-admin').className = role === 'admin' ? 'role-btn admin-active' : 'role-btn inactive';
            document.getElementById('btn-role-staff').className = role === 'staff' ? 'role-btn staff-active' : 'role-btn inactive';

            document.querySelectorAll('.admin-only').forEach(el => {
                el.style.display = role === 'admin' ? 'flex' : 'none';
            });

            if (role === 'staff') {
                showSection('attendance-site', document.querySelectorAll('.nav-item')[2]);
            } else {
                showSection('dashboard', document.querySelectorAll('.nav-item')[0]);
            }
        }

        // 1. Add or Edit Staff
        function saveStaff(e) {
            e.preventDefault();
            const editId = document.getElementById('edit-staff-id').value;
            const name = document.getElementById('staff-name').value.trim();
            const phone = document.getElementById('staff-phone').value.trim();
            const role = document.getElementById('staff-role').value.trim();
            const wage = parseFloat(document.getElementById('staff-wage').value);

            if (editId) {
                // Update existing staff
                staffList = staffList.map(s => {
                    if (s.id === editId) {
                        return { ...s, name, phone, role, wage };
                    }
                    return s;
                });

                // Update staff name in other records
                attendanceList = attendanceList.map(a => a.staffId === editId ? { ...a, staffName: name } : a);
                otList = otList.map(o => o.staffId === editId ? { ...o, staffName: name } : o);
                paymentList = paymentList.map(p => p.staffId === editId ? { ...p, staffName: name } : p);

                localStorage.setItem('wf_attendance', JSON.stringify(attendanceList));
                localStorage.setItem('wf_ot', JSON.stringify(otList));
                localStorage.setItem('wf_payments', JSON.stringify(paymentList));

                alert('Staff details updated successfully!');
            } else {
                // Add new staff
                const newStaff = {
                    id: Date.now().toString(),
                    name,
                    phone,
                    role,
                    wage
                };
                staffList.push(newStaff);
                alert('Staff added successfully!');
            }

            localStorage.setItem('wf_staff', JSON.stringify(staffList));
            cancelStaffEdit();
            updateAllUI();
        }

        function startEditStaff(id) {
            const staff = staffList.find(s => s.id === id);
            if (!staff) return;

            document.getElementById('edit-staff-id').value = staff.id;
            document.getElementById('staff-name').value = staff.name;
            document.getElementById('staff-phone').value = staff.phone;
            document.getElementById('staff-role').value = staff.role;
            document.getElementById('staff-wage').value = staff.wage;

            document.getElementById('staff-form-title').innerText = 'Edit Staff Details (സ്റ്റാഫ് വിവരങ്ങൾ തിരുത്തുക)';
            document.getElementById('staff-submit-btn').innerText = 'Update Staff';
            document.getElementById('staff-cancel-btn').style.display = 'inline-block';
        }

        function cancelStaffEdit() {
            document.getElementById('staff-form').reset();
            document.getElementById('edit-staff-id').value = '';
            document.getElementById('staff-form-title').innerText = 'Add New Staff (പുതിയ സ്റ്റാഫിനെ ചേർക്കുക)';
            document.getElementById('staff-submit-btn').innerText = '+ Save Staff';
            document.getElementById('staff-cancel-btn').style.display = 'none';
        }

        // 2. Add Attendance & Site
        function addAttendance(e) {
            e.preventDefault();
            const staffId = document.getElementById('att-staff').value;
            const staff = staffList.find(s => s.id === staffId);
            if(!staff) return alert('Please add a staff member first!');

            const status = document.getElementById('att-status').value;
            let earned = 0;
            if(status === 'Present') earned = staff.wage;
            if(status === 'Half Day') earned = staff.wage / 2;

            const record = {
                id: Date.now(),
                staffId: staff.id,
                staffName: staff.name,
                date: document.getElementById('att-date').value,
                site: document.getElementById('att-site').value,
                status: status,
                earned: earned,
                addedBy: currentRole.toUpperCase()
            };
            attendanceList.push(record);
            localStorage.setItem('wf_attendance', JSON.stringify(attendanceList));
            document.getElementById('att-site').value = '';
            updateAllUI();
            alert('Attendance & Site Recorded!');
        }

        // 3. Add OT
        function addOT(e) {
            e.preventDefault();
            const staffId = document.getElementById('ot-staff').value;
            const staff = staffList.find(s => s.id === staffId);
            if(!staff) return alert('Please select a staff!');

            const record = {
                id: Date.now(),
                staffId: staff.id,
                staffName: staff.name,
                date: document.getElementById('ot-date').value,
                site: document.getElementById('ot-site').value,
                hours: parseFloat(document.getElementById('ot-hours').value),
                amount: parseFloat(document.getElementById('ot-amount').value)
            };
            otList.push(record);
            localStorage.setItem('wf_ot', JSON.stringify(otList));
            e.target.reset();
            document.getElementById('ot-date').value = today;
            updateAllUI();
            alert('OT Recorded!');
        }

        // 4. Add Payment / Advance
        function addPayment(e) {
            e.preventDefault();
            const staffId = document.getElementById('pay-staff').value;
            const staff = staffList.find(s => s.id === staffId);
            if(!staff) return alert('Please select a staff!');

            const record = {
                id: Date.now(),
                staffId: staff.id,
                staffName: staff.name,
                date: document.getElementById('pay-date').value,
                type: document.getElementById('pay-type').value,
                amount: parseFloat(document.getElementById('pay-amount').value),
                note: document.getElementById('pay-note').value || '-'
            };
            paymentList.push(record);
            localStorage.setItem('wf_payments', JSON.stringify(paymentList));
            e.target.reset();
            document.getElementById('pay-date').value = today;
            updateAllUI();
            alert('Payment Recorded!');
        }

        // Delete Item Helper
        function deleteItem(type, id) {
            if(!confirm('Are you sure you want to delete this record?')) return;
            if(type === 'staff') {
                staffList = staffList.filter(i => i.id !== id.toString());
                localStorage.setItem('wf_staff', JSON.stringify(staffList));
                if(document.getElementById('edit-staff-id').value === id.toString()) {
                    cancelStaffEdit();
                }
            } else if(type === 'att') {
                attendanceList = attendanceList.filter(i => i.id !== id);
                localStorage.setItem('wf_attendance', JSON.stringify(attendanceList));
            } else if(type === 'ot') {
                otList = otList.filter(i => i.id !== id);
                localStorage.setItem('wf_ot', JSON.stringify(otList));
            } else if(type === 'pay') {
                paymentList = paymentList.filter(i => i.id !== id);
                localStorage.setItem('wf_payments', JSON.stringify(paymentList));
            }
            updateAllUI();
        }

        function updateAllUI() {
            const dropdowns = ['att-staff', 'ot-staff', 'pay-staff'];
            dropdowns.forEach(id => {
                const select = document.getElementById(id);
                select.innerHTML = staffList.length ? '' : '<option value="">No Staff Added</option>';
                staffList.forEach(s => {
                    select.innerHTML += `<option value="${s.id}">${s.name} (${s.role})</option>`;
                });
            });

            const staffTable = document.getElementById('staff-list-table');
            staffTable.innerHTML = staffList.map(s => `
                <tr>
                    <td><strong>${s.name}</strong></td>
                    <td>${s.phone}</td>
                    <td>${s.role}</td>
                    <td>₹${s.wage}/day</td>
                    <td>
                        <button class="btn-edit" onclick="startEditStaff('${s.id}')">Edit</button>
                        <button class="btn-del" onclick="deleteItem('staff', '${s.id}')">Delete</button>
                    </td>
                </tr>
            `).join('');

            const attTable = document.getElementById('attendance-table');
            attTable.innerHTML = attendanceList.slice().reverse().map(a => {
                let badge = a.status === 'Present' ? 'badge-present' : (a.status === 'Half Day' ? 'badge-half' : 'badge-absent');
                return `
                <tr>
                    <td>${a.date}</td>
                    <td>${a.staffName}</td>
                    <td>📍 ${a.site}</td>
                    <td><span class="badge ${badge}">${a.status}</span></td>
                    <td>₹${a.earned}</td>
                    <td><small>${a.addedBy}</small></td>
                    <td><button class="btn-del" onclick="deleteItem('att', ${a.id})">X</button></td>
                </tr>`;
            }).join('');

            document.getElementById('dashboard-recent-table').innerHTML = attendanceList.slice(-5).reverse().map(a => `
                <tr>
                    <td>${a.date}</td>
                    <td>${a.staffName}</td>
                    <td>${a.site}</td>
                    <td>${a.status}</td>
                    <td>${a.addedBy}</td>
                </tr>
            `).join('');

            const otTable = document.getElementById('ot-table');
            otTable.innerHTML = otList.slice().reverse().map(o => `
                <tr>
                    <td>${o.date}</td>
                    <td>${o.staffName}</td>
                    <td>${o.site}</td>
                    <td>${o.hours} Hrs</td>
                    <td>₹${o.amount}</td>
                    <td><button class="btn-del" onclick="deleteItem('ot', ${o.id})">X</button></td>
                </tr>
            `).join('');

            const paymentTable = document.getElementById('payment-table');
            paymentTable.innerHTML = paymentList.slice().reverse().map(p => `
                <tr>
                    <td>${p.date}</td>
                    <td>${p.staffName}</td>
                    <td><strong>${p.type}</strong></td>
                    <td>₹${p.amount}</td>
                    <td>${p.note}</td>
                    <td><button class="btn-del" onclick="deleteItem('pay', ${p.id})">X</button></td>
                </tr>
            `).join('');

            let totalPaidGlobal = 0;
            let totalBalanceGlobal = 0;

            const salaryTable = document.getElementById('salary-summary-table');
            salaryTable.innerHTML = staffList.map(s => {
                const staffAtt = attendanceList.filter(a => a.staffId === s.id);
                const daysWorked = staffAtt.reduce((sum, a) => sum + (a.status === 'Present' ? 1 : (a.status === 'Half Day' ? 0.5 : 0)), 0);
                const basicTotal = staffAtt.reduce((sum, a) => sum + a.earned, 0);
                
                const otTotal = otList.filter(o => o.staffId === s.id).reduce((sum, o) => sum + o.amount, 0);
                const grossSalary = basicTotal + otTotal;
                
                const paidTotal = paymentList.filter(p => p.staffId === s.id).reduce((sum, p) => sum + p.amount, 0);
                const balance = grossSalary - paidTotal;

                totalPaidGlobal += paidTotal;
                totalBalanceGlobal += balance;

                return `
                <tr>
                    <td><strong>${s.name}</strong></td>
                    <td>${daysWorked} Days</td>
                    <td>₹${basicTotal}</td>
                    <td>₹${otTotal}</td>
                    <td><strong>₹${grossSalary}</strong></td>
                    <td style="color: var(--danger);">₹${paidTotal}</td>
                    <td style="color: var(--success); font-weight: bold; font-size: 15px;">₹${balance}</td>
                </tr>`;
            }).join('');

            document.getElementById('stat-total-staff').innerText = staffList.length;
            const todayPresentCount = attendanceList.filter(a => a.date === today && a.status !== 'Absent').length;
            document.getElementById('stat-today-present').innerText = todayPresentCount;
            document.getElementById('stat-total-paid').innerText = '₹' + totalPaidGlobal;
            document.getElementById('stat-net-balance').innerText = '₹' + totalBalanceGlobal;
        }

        updateAllUI();
    </script>
</body>
</html>
