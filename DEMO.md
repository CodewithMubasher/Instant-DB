# 🎬 Instant-DB - Interactive Demo Guide

Welcome to the **Instant-DB Demo**! Follow these steps to master all features in 5 minutes.

---

## 🎯 Demo Flow Overview

```
⏱️  Total Time: ~5 minutes
📊 Difficulty: Beginner-Friendly
✨ Features Covered: All major features
```

---

## 1️⃣ Getting Started (1 min)

### Step 1: Open the Application
```
1. Open index.html in your web browser
2. Wait for the interface to load
3. You should see the main dashboard
```

### Step 2: Load Sample Data
```
- Click "Load Sample Database" button
  OR
- Drag & drop your own SQLite database file
  OR
- Click "Create New Database"
```

✅ **Goal**: See the main dashboard with tables listed in the sidebar

---

## 2️⃣ Explore Table Data (1 min)

### Step 1: View Tables
```
1. Look at the left sidebar - all tables are listed
2. Click on any table name to view its data
3. Scroll through the rows using virtual scrolling
```

### Step 2: Understanding the Layout
```
📍 Left Sidebar: Table list + quick actions
📍 Main Panel: Data grid view
📍 Top Toolbar: Search, filter, view options
📍 Right Panel: Table details + statistics
```

### Step 3: Search Data
```
1. Click the Search icon (🔍)
2. Type any value to search across all columns
3. Results highlight instantly
4. Clear to reset
```

✅ **Goal**: Find a specific row using search

---

## 3️⃣ Advanced Filtering (1 min)

### Step 1: Apply Filters
```
1. Click on any column header
2. Select "Filter" option
3. Choose your condition:
   - Equals
   - Contains
   - Greater Than
   - Less Than
4. Enter the value
5. Click Apply
```

### Step 2: Combine Filters
```
1. Add multiple filters to narrow down results
2. Use AND/OR logic
3. See results update in real-time
```

### Step 3: Sort Data
```
1. Click column header
2. Select "Sort Ascending" or "Sort Descending"
3. Multiple column sorting available
```

✅ **Goal**: Filter and sort data like a pro

---

## 4️⃣ View ER Diagram (1 min)

### Step 1: Open ER Diagram
```
1. Click "ER Diagram" button in toolbar
2. See all tables and their relationships
3. Nodes show table names
4. Lines show foreign key relationships
```

### Step 2: Understand Relationships
```
- One-to-Many: 1 → ∞
- Many-to-Many: ∞ → ∞
- Colors indicate relationship types
- Hover to highlight related tables
```

### Step 3: Navigate Diagram
```
1. Drag to move around
2. Scroll to zoom
3. Click node to view table
4. Double-click to expand details
```

✅ **Goal**: Understand your database structure visually

---

## 5️⃣ Edit Data Inline (1 min)

### Step 1: Start Editing
```
1. Click any cell in the data grid
2. Cell becomes editable
3. Type your changes
4. Press Enter to confirm
5. Or Escape to cancel
```

### Step 2: See Changes
```
- Cell highlights to show it's been modified
- Changes preview in real-time
- Other cells update if linked
```

### Step 3: Undo/Redo
```
1. Made a mistake? Click "Undo" (⌘Z / Ctrl+Z)
2. Or "Redo" (⌘Y / Ctrl+Y)
3. Full edit history available
4. Revert to original anytime
```

✅ **Goal**: Edit a record and undo the changes

---

## 6️⃣ Use SQL Editor (Advanced - 1 min)

### Step 1: Open SQL Editor
```
1. Click "SQL Editor" button
2. See the SQL query input area
3. Sample queries available
```

### Step 2: Write a Query
```
Example queries:

-- Select all users
SELECT * FROM users;

-- Find active users
SELECT * FROM users WHERE status = 'active';

-- Count by category
SELECT category, COUNT(*) as count FROM products GROUP BY category;

-- Join tables
SELECT u.name, o.order_id FROM users u JOIN orders o ON u.id = o.user_id;
```

### Step 3: Execute Query
```
1. Write or paste your SQL
2. Click "Execute" (▶️) button
3. See results in the output panel
4. Export results if needed
```

### Step 4: View Query History
```
1. Click "History" tab
2. See all past queries
3. Re-run any query with one click
4. Save favorite queries
```

✅ **Goal**: Write and execute a SQL query

---

## 7️⃣ Data Analytics & Profiling (1 min)

### Step 1: Open Analytics
```
1. Click "Analytics" tab
2. See data statistics
3. View column info
```

### Step 2: Explore Statistics
```
Shows for each column:
- Data Type
- Not Null Count
- Unique Values
- Min/Max Values (numeric)
- Null Percentage
```

### Step 3: Use AI Assistant (Optional)
```
1. Click "AI Assistant" button
2. Ask questions about your data:
   - "What are the top 5 products?"
   - "Show me duplicate records"
   - "Find outliers in sales"
3. Get instant insights
4. Requires API key (OpenAI, Claude, etc.)
```

✅ **Goal**: Get insights from your data

---

## 8️⃣ Customize Appearance (Optional)

### Step 1: Toggle Theme
```
1. Click Theme button (🌙/☀️)
2. Switch between Dark and Light modes
3. Preference saves automatically
```

### Step 2: Adjust View Options
```
- Column visibility toggles
- Row height adjustment
- Grid density options
- Density: Compact/Normal/Spacious
```

### Step 3: Export Data
```
1. Right-click on table
2. Select "Export as CSV"
3. Or "Export as JSON"
4. File downloads automatically
```

✅ **Goal**: Customize the interface to your preference

---

## 🎯 Quick Command Reference

### Keyboard Shortcuts
```
⌘/Ctrl + F        → Search
⌘/Ctrl + Z        → Undo
⌘/Ctrl + Y        → Redo
⌘/Ctrl + S        → Save
Enter              → Confirm edit
Escape             → Cancel edit
Space              → Toggle row selection
Arrow Keys         → Navigate cells
```

### Common Tasks
```
📊 Load database      → Drag & drop or click Load
🔍 Search data        → Click Search, type value
📈 View statistics    → Click Analytics tab
🗺️  View relationships → Click ER Diagram
💬 Get AI help        → Click AI Assistant
```

---

## 💡 Pro Tips

### Tip 1: Virtual Scrolling
- Handles 1M+ rows smoothly
- Scroll works instantly, no lag
- Memory efficient

### Tip 2: Keyboard Navigation
- Use arrow keys to move between cells
- Fast navigation with keyboard
- No mouse needed

### Tip 3: Filter Combinations
- Build complex filters
- Use AND/OR operators
- Save filter presets

### Tip 4: Query History
- All queries auto-save
- Quick access to past work
- Learn from history

### Tip 5: Dark Mode
- Easy on the eyes
- Great for long sessions
- Toggle anytime

---

## 🆘 Troubleshooting

### Issue: Database won't load
**Solution:**
- Check file is valid SQLite (.db, .sqlite, .sqlite3)
- Try sample data first
- Check browser console for errors

### Issue: Edits not working
**Solution:**
- Make sure table is writable
- Check column is not locked
- Try single column edit first

### Issue: Slow performance
**Solution:**
- Reduce active filters
- Try virtual scrolling
- Check browser resources
- Close other tabs

### Issue: AI Assistant not working
**Solution:**
- Add API key in settings
- Check internet connection
- Verify API key is valid
- Check API usage limits

---

## 🎓 Next Steps

After completing this demo:

1. **Try with Your Data**
   - Load your own database
   - Explore your structure
   - Run queries

2. **Learn SQL**
   - Start with simple SELECT
   - Practice JOINs
   - Try aggregations

3. **Contribute**
   - Found a bug? Report it
   - Have ideas? Share them
   - Want to help? Check CONTRIBUTING.md

4. **Share & Explore**
   - Star on GitHub ⭐
   - Share with friends
   - Join discussions

---

## 📞 Need Help?

- 📖 Read the main [README.md](README.md)
- 🐛 [Report Issues](https://github.com/CodewithMubasher/Instant-DB/issues)
- 💬 [Join Discussions](https://github.com/CodewithMubasher/Instant-DB/discussions)
- 👨‍💻 [View Source Code](https://github.com/CodewithMubasher/Instant-DB)

---

<div align="center">

### 🎉 Congratulations!

You've completed the Instant-DB demo! You're now ready to use it with your own databases.

**Happy Database Exploring! 🚀**

</div>
