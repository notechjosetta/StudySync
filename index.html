<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StudySync - Academic Life Organizer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/marked/9.1.2/marked.min.js"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        'primary-dark': '#4A49B8',
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white dark:bg-gray-900 text-gray-900 dark:text-white transition-colors">
    <div id="app" class="min-h-screen">
        <!-- Navigation -->
        <nav class="bg-primary dark:bg-primary-dark text-white p-4 shadow-lg">
            <div class="max-w-7xl mx-auto flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <i class="fas fa-graduation-cap text-2xl"></i>
                    <h1 class="text-xl font-bold">StudySync</h1>
                </div>
                <div class="flex space-x-1 overflow-x-auto">
                    <button onclick="switchView('dashboard')" class="nav-btn px-3 py-2 rounded-lg transition-colors text-sm whitespace-nowrap" data-view="dashboard">
                        <i class="fas fa-home mr-1"></i>Dashboard
                    </button>
                    <button onclick="switchView('tasks')" class="nav-btn px-3 py-2 rounded-lg transition-colors text-sm whitespace-nowrap" data-view="tasks">
                        <i class="fas fa-tasks mr-1"></i>Tasks
                    </button>
                    <button onclick="switchView('calendar')" class="nav-btn px-3 py-2 rounded-lg transition-colors text-sm whitespace-nowrap" data-view="calendar">
                        <i class="fas fa-calendar mr-1"></i>Calendar
                    </button>
                    <button onclick="switchView('notes')" class="nav-btn px-3 py-2 rounded-lg transition-colors text-sm whitespace-nowrap" data-view="notes">
                        <i class="fas fa-sticky-note mr-1"></i>Notes
                    </button>
                    <button onclick="switchView('study')" class="nav-btn px-3 py-2 rounded-lg transition-colors text-sm whitespace-nowrap" data-view="study">
                        <i class="fas fa-brain mr-1"></i>Study
                    </button>
                </div>
            </div>
        </nav>

        <!-- Main Content -->
        <main class="max-w-7xl mx-auto p-4">
            <!-- Dashboard View -->
            <div id="dashboard-view" class="view">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold mb-4">Dashboard</h2>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4 mb-6">
                        <div class="bg-blue-100 dark:bg-blue-900 p-4 rounded-lg">
                            <div class="flex items-center justify-between">
                                <div>
                                    <p class="text-blue-800 dark:text-blue-200 text-sm">Pending Tasks</p>
                                    <p class="text-2xl font-bold text-blue-900 dark:text-blue-100" id="pending-count">0</p>
                                </div>
                                <i class="fas fa-tasks text-blue-600 text-2xl"></i>
                            </div>
                        </div>
                        <div class="bg-green-100 dark:bg-green-900 p-4 rounded-lg">
                            <div class="flex items-center justify-between">
                                <div>
                                    <p class="text-green-800 dark:text-green-200 text-sm">Completed Today</p>
                                    <p class="text-2xl font-bold text-green-900 dark:text-green-100" id="completed-count">0</p>
                                </div>
                                <i class="fas fa-check text-green-600 text-2xl"></i>
                            </div>
                        </div>
                        <div class="bg-yellow-100 dark:bg-yellow-900 p-4 rounded-lg">
                            <div class="flex items-center justify-between">
                                <div>
                                    <p class="text-yellow-800 dark:text-yellow-200 text-sm">Due This Week</p>
                                    <p class="text-2xl font-bold text-yellow-900 dark:text-yellow-100" id="due-week-count">0</p>
                                </div>
                                <i class="fas fa-clock text-yellow-600 text-2xl"></i>
                            </div>
                        </div>
                        <div class="bg-purple-100 dark:bg-purple-900 p-4 rounded-lg">
                            <div class="flex items-center justify-between">
                                <div>
                                    <p class="text-purple-800 dark:text-purple-200 text-sm">Study Cards</p>
                                    <p class="text-2xl font-bold text-purple-900 dark:text-purple-100" id="cards-count">0</p>
                                </div>
                                <i class="fas fa-brain text-purple-600 text-2xl"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold mb-4">Upcoming Deadlines</h3>
                        <div id="upcoming-deadlines" class="space-y-2">
                            <p class="text-gray-500 dark:text-gray-400">No upcoming deadlines</p>
                        </div>
                    </div>
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold mb-4">Recent Notes</h3>
                        <div id="recent-notes" class="space-y-2">
                            <p class="text-gray-500 dark:text-gray-400">No recent notes</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Tasks View -->
            <div id="tasks-view" class="view hidden">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-2xl font-bold">Task Management</h2>
                    <button onclick="showTaskForm()" class="bg-primary hover:bg-primary-dark text-white px-4 py-2 rounded-lg">
                        <i class="fas fa-plus mr-2"></i>Add Task
                    </button>
                </div>

                <div class="mb-4 flex flex-wrap gap-2">
                    <button onclick="filterTasks('all')" class="filter-btn px-3 py-1 rounded-full text-sm bg-primary text-white" data-filter="all">All</button>
                    <button onclick="filterTasks('pending')" class="filter-btn px-3 py-1 rounded-full text-sm bg-gray-200 dark:bg-gray-700" data-filter="pending">Pending</button>
                    <button onclick="filterTasks('completed')" class="filter-btn px-3 py-1 rounded-full text-sm bg-gray-200 dark:bg-gray-700" data-filter="completed">Completed</button>
                    <button onclick="filterTasks('overdue')" class="filter-btn px-3 py-1 rounded-full text-sm bg-gray-200 dark:bg-gray-700" data-filter="overdue">Overdue</button>
                </div>

                <div id="tasks-list" class="space-y-4">
                    <!-- Tasks will be rendered here -->
                </div>
            </div>

            <!-- Calendar View -->
            <div id="calendar-view" class="view hidden">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-2xl font-bold">Calendar</h2>
                    <div class="flex items-center space-x-4">
                        <button onclick="previousMonth()" class="p-2 rounded-lg bg-gray-200 dark:bg-gray-700 hover:bg-gray-300 dark:hover:bg-gray-600">
                            <i class="fas fa-chevron-left"></i>
                        </button>
                        <span id="current-month" class="font-semibold text-lg"></span>
                        <button onclick="nextMonth()" class="p-2 rounded-lg bg-gray-200 dark:bg-gray-700 hover:bg-gray-300 dark:hover:bg-gray-600">
                            <i class="fas fa-chevron-right"></i>
                        </button>
                    </div>
                </div>

                <div class="grid grid-cols-7 gap-1 mb-4">
                    <div class="text-center font-semibold p-2">Sun</div>
                    <div class="text-center font-semibold p-2">Mon</div>
                    <div class="text-center font-semibold p-2">Tue</div>
                    <div class="text-center font-semibold p-2">Wed</div>
                    <div class="text-center font-semibold p-2">Thu</div>
                    <div class="text-center font-semibold p-2">Fri</div>
                    <div class="text-center font-semibold p-2">Sat</div>
                </div>

                <div id="calendar-grid" class="grid grid-cols-7 gap-1">
                    <!-- Calendar days will be rendered here -->
                </div>
            </div>

            <!-- Notes View -->
            <div id="notes-view" class="view hidden">
                <div class="flex justify-between items-center mb-6">
                    <h2 class="text-2xl font-bold">Notes</h2>
                    <button onclick="showNoteForm()" class="bg-primary hover:bg-primary-dark text-white px-4 py-2 rounded-lg">
                        <i class="fas fa-plus mr-2"></i>Add Note
                    </button>
                </div>

                <div class="mb-4">
                    <input type="text" id="note-search" placeholder="Search notes..." class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent">
                </div>

                <div class="mb-4 flex flex-wrap gap-2">
                    <button onclick="filterNotes('all')" class="note-filter-btn px-3 py-1 rounded-full text-sm bg-primary text-white" data-filter="all">All</button>
                    <div id="subject-filters"></div>
                </div>

                <div id="notes-list" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                    <!-- Notes will be rendered here -->
                </div>
            </div>

            <!-- Study Tools View -->
            <div id="study-view" class="view hidden">
                <h2 class="text-2xl font-bold mb-6">Study Tools</h2>
                
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-lg">
                        <div class="flex justify-between items-center mb-4">
                            <h3 class="text-lg font-semibold">Flashcards</h3>
                            <button onclick="showFlashcardForm()" class="bg-primary hover:bg-primary-dark text-white px-3 py-2 rounded-lg text-sm">
                                <i class="fas fa-plus mr-1"></i>Add Card
                            </button>
                        </div>
                        <div id="flashcards-list" class="space-y-2">
                            <p class="text-gray-500 dark:text-gray-400">No flashcards yet</p>
                        </div>
                    </div>

                    <div class="bg-gray-50 dark:bg-gray-800 p-6 rounded-lg">
                        <h3 class="text-lg font-semibold mb-4">Study Session</h3>
                        <div id="study-session" class="text-center">
                            <p class="text-gray-500 dark:text-gray-400 mb-4">Start a study session with your flashcards</p>
                            <button onclick="startStudySession()" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-lg">
                                <i class="fas fa-play mr-2"></i>Start Session
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </main>

        <!-- Task Form Modal -->
        <div id="task-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-md w-full mx-4">
                <h3 class="text-lg font-semibold mb-4">Add New Task</h3>
                <form id="task-form">
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Title</label>
                        <input type="text" id="task-title" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent" required>
                    </div>
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Subject</label>
                        <input type="text" id="task-subject" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent">
                    </div>
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Due Date</label>
                        <input type="date" id="task-due-date" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent">
                    </div>
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Priority</label>
                        <select id="task-priority" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent">
                            <option value="low">Low</option>
                            <option value="medium">Medium</option>
                            <option value="high">High</option>
                        </select>
                    </div>
                    <div class="mb-6">
                        <label class="block text-sm font-medium mb-2">Description</label>
                        <textarea id="task-description" rows="3" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent"></textarea>
                    </div>
                    <div class="flex justify-end space-x-3">
                        <button type="button" onclick="hideTaskForm()" class="px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded-lg">Cancel</button>
                        <button type="submit" class="px-4 py-2 bg-primary hover:bg-primary-dark text-white rounded-lg">Add Task</button>
                    </div>
                </form>
            </div>
        </div>

        <!-- Note Form Modal -->
        <div id="note-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-2xl w-full mx-4 max-h-[90vh] overflow-y-auto">
                <h3 class="text-lg font-semibold mb-4">Add New Note</h3>
                <form id="note-form">
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Title</label>
                        <input type="text" id="note-title" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent" required>
                    </div>
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Subject</label>
                        <input type="text" id="note-subject" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent">
                    </div>
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Tags (comma-separated)</label>
                        <input type="text" id="note-tags" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="e.g., important, exam, chapter1">
                    </div>
                    <div class="mb-6">
                        <label class="block text-sm font-medium mb-2">Content (Markdown supported)</label>
                        <textarea id="note-content" rows="8" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Write your notes here..."></textarea>
                    </div>
                    <div class="flex justify-end space-x-3">
                        <button type="button" onclick="hideNoteForm()" class="px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded-lg">Cancel</button>
                        <button type="submit" class="px-4 py-2 bg-primary hover:bg-primary-dark text-white rounded-lg">Save Note</button>
                    </div>
                </form>
            </div>
        </div>

        <!-- Flashcard Form Modal -->
        <div id="flashcard-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
            <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-md w-full mx-4">
                <h3 class="text-lg font-semibold mb-4">Add Flashcard</h3>
                <form id="flashcard-form">
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Subject</label>
                        <input type="text" id="flashcard-subject" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent">
                    </div>
                    <div class="mb-4">
                        <label class="block text-sm font-medium mb-2">Front (Question)</label>
                        <textarea id="flashcard-front" rows="3" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent" required></textarea>
                    </div>
                    <div class="mb-6">
                        <label class="block text-sm font-medium mb-2">Back (Answer)</label>
                        <textarea id="flashcard-back" rows="3" class="w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg bg-white dark:bg-gray-800 focus:ring-2 focus:ring-primary focus:border-transparent" required></textarea>
                    </div>
                    <div class="flex justify-end space-x-3">
                        <button type="button" onclick="hideFlashcardForm()" class="px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded-lg">Cancel</button>
                        <button type="submit" class="px-4 py-2 bg-primary hover:bg-primary-dark text-white rounded-lg">Add Card</button>
                    </div>
                </form>
            </div>
        </div>
    </div>

    <script>
        // Dark mode setup
        if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.documentElement.classList.add('dark');
        }
        window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', event => {
            if (event.matches) {
                document.documentElement.classList.add('dark');
            } else {
                document.documentElement.classList.remove('dark');
            }
        });

        // App state
        let currentView = 'dashboard';
        let currentFilter = 'all';
        let currentMonth = new Date().getMonth();
        let currentYear = new Date().getFullYear();
        let editingTask = null;
        let editingNote = null;
        let studySessionActive = false;
        let currentCardIndex = 0;

        // Data storage
        const data = {
            tasks: [],
            notes: [],
            flashcards: []
        };

        // Initialize app
        document.addEventListener('DOMContentLoaded', function() {
            // Sample data
            data.tasks = [
                {
                    id: 1,
                    title: 'Physics Assignment',
                    subject: 'Physics',
                    description: 'Chapter 5 problems 1-15',
                    dueDate: new Date(Date.now() + 2 * 24 * 60 * 60 * 1000).toISOString().split('T')[0],
                    priority: 'high',
                    completed: false,
                    createdAt: new Date()
                },
                {
                    id: 2,
                    title: 'History Essay',
                    subject: 'History',
                    description: 'Write essay on World War II',
                    dueDate: new Date(Date.now() + 5 * 24 * 60 * 60 * 1000).toISOString().split('T')[0],
                    priority: 'medium',
                    completed: false,
                    createdAt: new Date()
                }
            ];

            data.notes = [
                {
                    id: 1,
                    title: 'Newton\'s Laws',
                    subject: 'Physics',
                    content: '# Newton\'s Laws of Motion\n\n1. **First Law**: An object at rest stays at rest...\n2. **Second Law**: F = ma\n3. **Third Law**: For every action, there is an equal and opposite reaction',
                    tags: ['physics', 'mechanics', 'laws'],
                    createdAt: new Date(),
                    updatedAt: new Date()
                }
            ];

            data.flashcards = [
                {
                    id: 1,
                    subject: 'Physics',
                    front: 'What is Newton\'s Second Law?',
                    back: 'F = ma (Force equals mass times acceleration)',
                    createdAt: new Date()
                }
            ];

            switchView('dashboard');
            updateDashboard();
            renderCalendar();
        });

        // Navigation
        function switchView(view) {
            currentView = view;
            
            // Hide all views
            document.querySelectorAll('.view').forEach(v => v.classList.add('hidden'));
            
            // Show selected view
            document.getElementById(view + '-view').classList.remove('hidden');
            
            // Update navigation
            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.classList.remove('bg-white', 'bg-opacity-20');
                if (btn.dataset.view === view) {
                    btn.classList.add('bg-white', 'bg-opacity-20');
                }
            });

            // Render view content
            switch(view) {
                case 'dashboard':
                    updateDashboard();
                    break;
                case 'tasks':
                    renderTasks();
                    break;
                case 'calendar':
                    renderCalendar();
                    break;
                case 'notes':
                    renderNotes();
                    renderSubjectFilters();
                    break;
                case 'study':
                    renderFlashcards();
                    break;
            }
        }

        // Dashboard
        function updateDashboard() {
            const pending = data.tasks.filter(t => !t.completed).length;
            const completedToday = data.tasks.filter(t => t.completed && isToday(new Date(t.updatedAt || t.createdAt))).length;
            const dueThisWeek = data.tasks.filter(t => !t.completed && isThisWeek(new Date(t.dueDate))).length;
            
            document.getElementById('pending-count').textContent = pending;
            document.getElementById('completed-count').textContent = completedToday;
            document.getElementById('due-week-count').textContent = dueThisWeek;
            document.getElementById('cards-count').textContent = data.flashcards.length;

            // Upcoming deadlines
            const upcoming = data.tasks
                .filter(t => !t.completed && new Date(t.dueDate) >= new Date())
                .sort((a, b) => new Date(a.dueDate) - new Date(b.dueDate))
                .slice(0, 5);
            
            const deadlinesEl = document.getElementById('upcoming-deadlines');
            if (upcoming.length === 0) {
                deadlinesEl.innerHTML = '<p class="text-gray-500 dark:text-gray-400">No upcoming deadlines</p>';
            } else {
                deadlinesEl.innerHTML = upcoming.map(task => `
                    <div class="flex justify-between items-center p-2 bg-white dark:bg-gray-700 rounded">
                        <span class="font-medium">${task.title}</span>
                        <span class="text-sm text-gray-500 dark:text-gray-400">${formatDate(task.dueDate)}</span>
                    </div>
                `).join('');
            }

            // Recent notes
            const recent = data.notes
                .sort((a, b) => new Date(b.updatedAt) - new Date(a.updatedAt))
                .slice(0, 5);
            
            const notesEl = document.getElementById('recent-notes');
            if (recent.length === 0) {
                notesEl.innerHTML = '<p class="text-gray-500 dark:text-gray-400">No recent notes</p>';
            } else {
                notesEl.innerHTML = recent.map(note => `
                    <div class="p-2 bg-white dark:bg-gray-700 rounded cursor-pointer hover:bg-gray-50 dark:hover:bg-gray-600" onclick="switchView('notes')">
                        <div class="font-medium">${note.title}</div>
                        <div class="text-sm text-gray-500 dark:text-gray-400">${note.subject || 'General'}</div>
                    </div>
                `).join('');
            }
        }

        // Task Management
        function renderTasks() {
            let filteredTasks = data.tasks;
            
            switch(currentFilter) {
                case 'pending':
                    filteredTasks = data.tasks.filter(t => !t.completed);
                    break;
                case 'completed':
                    filteredTasks = data.tasks.filter(t => t.completed);
                    break;
                case 'overdue':
                    filteredTasks = data.tasks.filter(t => !t.completed && new Date(t.dueDate) < new Date());
                    break;
            }

            const tasksEl = document.getElementById('tasks-list');
            if (filteredTasks.length === 0) {
                tasksEl.innerHTML = '<p class="text-gray-500 dark:text-gray-400">No tasks found</p>';
                return;
            }

            tasksEl.innerHTML = filteredTasks.map(task => `
                <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow border-l-4 ${getPriorityColor(task.priority)}">
                    <div class="flex items-start justify-between">
                        <div class="flex items-start space-x-3 flex-1">
                            <input type="checkbox" ${task.completed ? 'checked' : ''} 
                                onchange="toggleTask(${task.id})" 
                                class="mt-1 w-4 h-4 text-primary bg-gray-100 border-gray-300 rounded focus:ring-primary dark:focus:ring-primary dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                            <div class="flex-1">
                                <h3 class="font-semibold ${task.completed ? 'line-through text-gray-500' : ''}">${task.title}</h3>
                                <p class="text-sm text-gray-600 dark:text-gray-400">${task.subject || 'General'}</p>
                                <p class="text-sm text-gray-500 dark:text-gray-500 mt-1">${task.description}</p>
                                <div class="flex items-center space-x-4 mt-2 text-xs text-gray-500 dark:text-gray-400">
                                    <span><i class="fas fa-calendar mr-1"></i>${formatDate(task.dueDate)}</span>
                                    <span class="px-2 py-1 rounded-full ${getPriorityBadgeColor(task.priority)}">${task.priority}</span>
                                </div>
                            </div>
                        </div>
                        <div class="flex space-x-2">
                            <button onclick="editTask(${task.id})" class="text-blue-500 hover:text-blue-700">
                                <i class="fas fa-edit"></i>
                            </button>
                            <button onclick="deleteTask(${task.id})" class="text-red-500 hover:text-red-700">
                                <i class="fas fa-trash"></i>
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        function filterTasks(filter) {
            currentFilter = filter;
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('bg-primary', 'text-white');
                btn.classList.add('bg-gray-200', 'dark:bg-gray-700');
                if (btn.dataset.filter === filter) {
                    btn.classList.remove('bg-gray-200', 'dark:bg-gray-700');
                    btn.classList.add('bg-primary', 'text-white');
                }
            });
            renderTasks();
        }

        function showTaskForm(taskId = null) {
            editingTask = taskId;
            const form = document.getElementById('task-form');
            
            if (taskId) {
                const task = data.tasks.find(t => t.id === taskId);
                document.getElementById('task-title').value = task.title;
                document.getElementById('task-subject').value = task.subject || '';
                document.getElementById('task-due-date').value = task.dueDate;
                document.getElementById('task-priority').value = task.priority;
                document.getElementById('task-description').value = task.description || '';
                document.querySelector('#task-modal h3').textContent = 'Edit Task';
                document.querySelector('#task-form button[type="submit"]').textContent = 'Update Task';
            } else {
                form.reset();
                document.querySelector('#task-modal h3').textContent = 'Add New Task';
                document.querySelector('#task-form button[type="submit"]').textContent = 'Add Task';
            }
            
            document.getElementById('task-modal').classList.remove('hidden');
        }

        function hideTaskForm() {
            document.getElementById('task-modal').classList.add('hidden');
            editingTask = null;
        }

        function editTask(id) {
            showTaskForm(id);
        }

        function deleteTask(id) {
            showConfirmDialog('Are you sure you want to delete this task?', () => {
                data.tasks = data.tasks.filter(t => t.id !== id);
                renderTasks();
                updateDashboard();
            });
        }

        function toggleTask(id) {
            const task = data.tasks.find(t => t.id === id);
            task.completed = !task.completed;
            task.updatedAt = new Date();
            renderTasks();
            updateDashboard();
        }

        // Calendar
        function renderCalendar() {
            const year = currentYear;
            const month = currentMonth;
            const firstDay = new Date(year, month, 1).getDay();
            const daysInMonth = new Date(year, month + 1, 0).getDate();
            
            document.getElementById('current-month').textContent = new Date(year, month).toLocaleString('default', { month: 'long', year: 'numeric' });
            
            const grid = document.getElementById('calendar-grid');
            grid.innerHTML = '';
            
            // Empty cells for days before month starts
            for (let i = 0; i < firstDay; i++) {
                grid.appendChild(createCalendarDay('', false));
            }
            
            // Days of the month
            for (let day = 1; day <= daysInMonth; day++) {
                const date = new Date(year, month, day);
                const dateString = date.toISOString().split('T')[0];
                const dayTasks = data.tasks.filter(t => t.dueDate === dateString);
                grid.appendChild(createCalendarDay(day, true, dayTasks, date));
            }
        }

        function createCalendarDay(day, isCurrentMonth, tasks = [], date = null) {
            const div = document.createElement('div');
            div.className = `min-h-[100px] p-2 border border-gray-200 dark:border-gray-700 ${isCurrentMonth ? 'bg-white dark:bg-gray-800' : 'bg-gray-50 dark:bg-gray-900'}`;
            
            if (date && isToday(date)) {
                div.classList.add('bg-blue-50', 'dark:bg-blue-900');
            }
            
            let content = `<div class="font-semibold text-sm mb-1">${day}</div>`;
            
            if (tasks && tasks.length > 0) {
                content += tasks.slice(0, 3).map(task => `
                    <div class="text-xs p-1 mb-1 rounded ${task.completed ? 'bg-green-100 dark:bg-green-900 text-green-800 dark:text-green-200' : 'bg-blue-100 dark:bg-blue-900 text-blue-800 dark:text-blue-200'} truncate">
                        ${task.title}
                    </div>
                `).join('');
                
                if (tasks.length > 3) {
                    content += `<div class="text-xs text-gray-500">+${tasks.length - 3} more</div>`;
                }
            }
            
            div.innerHTML = content;
            return div;
        }

        function previousMonth() {
            currentMonth--;
            if (currentMonth < 0) {
                currentMonth = 11;
                currentYear--;
            }
            renderCalendar();
        }

        function nextMonth() {
            currentMonth++;
            if (currentMonth > 11) {
                currentMonth = 0;
                currentYear++;
            }
            renderCalendar();
        }

        // Notes
        function renderNotes() {
            let filteredNotes = data.notes;
            
            const search = document.getElementById('note-search').value.toLowerCase();
            if (search) {
                filteredNotes = filteredNotes.filter(note => 
                    note.title.toLowerCase().includes(search) ||
                    note.content.toLowerCase().includes(search) ||
                    note.tags.some(tag => tag.toLowerCase().includes(search))
                );
            }
            
            if (currentFilter !== 'all') {
                filteredNotes = filteredNotes.filter(note => note.subject === currentFilter);
            }

            const notesEl = document.getElementById('notes-list');
            if (filteredNotes.length === 0) {
                notesEl.innerHTML = '<p class="text-gray-500 dark:text-gray-400 col-span-full">No notes found</p>';
                return;
            }

            notesEl.innerHTML = filteredNotes.map(note => `
                <div class="bg-white dark:bg-gray-800 p-4 rounded-lg shadow">
                    <div class="flex justify-between items-start mb-2">
                        <h3 class="font-semibold truncate">${note.title}</h3>
                        <div class="flex space-x-2">
                            <button onclick="editNote(${note.id})" class="text-blue-500 hover:text-blue-700">
                                <i class="fas fa-edit"></i>
                            </button>
                            <button onclick="deleteNote(${note.id})" class="text-red-500 hover:text-red-700">
                                <i class="fas fa-trash"></i>
                            </button>
                        </div>
                    </div>
                    <p class="text-sm text-gray-600 dark:text-gray-400 mb-2">${note.subject || 'General'}</p>
                    <div class="text-sm text-gray-700 dark:text-gray-300 mb-3 max-h-20 overflow-hidden">
                        ${marked.parse(note.content.substring(0, 150) + (note.content.length > 150 ? '...' : ''))}
                    </div>
                    <div class="flex flex-wrap gap-1 mb-2">
                        ${note.tags.map(tag => `<span class="px-2 py-1 text-xs bg-gray-100 dark:bg-gray-700 rounded-full">${tag}</span>`).join('')}
                    </div>
                    <p class="text-xs text-gray-500 dark:text-gray-400">${formatDate(note.updatedAt)}</p>
                </div>
            `).join('');
        }

        function renderSubjectFilters() {
            const subjects = [...new Set(data.notes.map(n => n.subject).filter(Boolean))];
            const filtersEl = document.getElementById('subject-filters');
            
            filtersEl.innerHTML = subjects.map(subject => `
                <button onclick="filterNotes('${subject}')" class="note-filter-btn px-3 py-1 rounded-full text-sm bg-gray-200 dark:bg-gray-700" data-filter="${subject}">
                    ${subject}
                </button>
            `).join('');
        }

        function filterNotes(filter) {
            currentFilter = filter;
            document.querySelectorAll('.note-filter-btn').forEach(btn => {
                btn.classList.remove('bg-primary', 'text-white');
                btn.classList.add('bg-gray-200', 'dark:bg-gray-700');
                if (btn.dataset.filter === filter) {
                    btn.classList.remove('bg-gray-200', 'dark:bg-gray-700');
                    btn.classList.add('bg-primary', 'text-white');
                }
            });
            renderNotes();
        }

        function showNoteForm(noteId = null) {
            editingNote = noteId;
            const form = document.getElementById('note-form');
            
            if (noteId) {
                const note = data.notes.find(n => n.id === noteId);
                document.getElementById('note-title').value = note.title;
                document.getElementById('note-subject').value = note.subject || '';
                document.getElementById('note-tags').value = note.tags.join(', ');
                document.getElementById('note-content').value = note.content;
                document.querySelector('#note-modal h3').textContent = 'Edit Note';
                document.querySelector('#note-form button[type="submit"]').textContent = 'Update Note';
            } else {
                form.reset();
                document.querySelector('#note-modal h3').textContent = 'Add New Note';
                document.querySelector('#note-form button[type="submit"]').textContent = 'Save Note';
            }
            
            document.getElementById('note-modal').classList.remove('hidden');
        }

        function hideNoteForm() {
            document.getElementById('note-modal').classList.add('hidden');
            editingNote = null;
        }

        function editNote(id) {
            showNoteForm(id);
        }

        function deleteNote(id) {
            showConfirmDialog('Are you sure you want to delete this note?', () => {
                data.notes = data.notes.filter(n => n.id !== id);
                renderNotes();
                renderSubjectFilters();
                updateDashboard();
            });
        }

        // Flashcards and Study Tools
        function renderFlashcards() {
            const flashcardsEl = document.getElementById('flashcards-list');
            
            if (data.flashcards.length === 0) {
                flashcardsEl.innerHTML = '<p class="text-gray-500 dark:text-gray-400">No flashcards yet</p>';
                return;
            }

            flashcardsEl.innerHTML = data.flashcards.map(card => `
                <div class="bg-white dark:bg-gray-700 p-3 rounded-lg border">
                    <div class="flex justify-between items-start">
                        <div class="flex-1">
                            <p class="text-sm font-medium">${card.subject || 'General'}</p>
                            <p class="text-sm text-gray-600 dark:text-gray-400 mt-1">${card.front.substring(0, 50)}${card.front.length > 50 ? '...' : ''}</p>
                        </div>
                        <button onclick="deleteFlashcard(${card.id})" class="text-red-500 hover:text-red-700 ml-2">
                            <i class="fas fa-trash text-sm"></i>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        function showFlashcardForm() {
            document.getElementById('flashcard-modal').classList.remove('hidden');
        }

        function hideFlashcardForm() {
            document.getElementById('flashcard-modal').classList.add('hidden');
            document.getElementById('flashcard-form').reset();
        }

        function deleteFlashcard(id) {
            showConfirmDialog('Are you sure you want to delete this flashcard?', () => {
                data.flashcards = data.flashcards.filter(f => f.id !== id);
                renderFlashcards();
                updateDashboard();
            });
        }

        function startStudySession() {
            if (data.flashcards.length === 0) {
                showAlert('No flashcards available. Add some flashcards first!');
                return;
            }

            studySessionActive = true;
            currentCardIndex = 0;
            showStudyCard();
        }

        function showStudyCard() {
            const card = data.flashcards[currentCardIndex];
            const sessionEl = document.getElementById('study-session');
            
            sessionEl.innerHTML = `
                <div class="bg-white dark:bg-gray-700 p-6 rounded-lg border">
                    <div class="text-sm text-gray-500 dark:text-gray-400 mb-2">Card ${currentCardIndex + 1} of ${data.flashcards.length}</div>
                    <div class="text-sm font-medium text-primary mb-4">${card.subject || 'General'}</div>
                    <div id="card-content" class="mb-4">
                        <div class="text-lg font-medium mb-4">${card.front}</div>
                        <button onclick="showAnswer()" class="bg-primary hover:bg-primary-dark text-white px-4 py-2 rounded-lg">Show Answer</button>
                    </div>
                    <div class="flex justify-between mt-4">
                        <button onclick="endSession()" class="text-gray-500 hover:text-gray-700">End Session</button>
                        <div class="space-x-2">
                            <button onclick="previousCard()" ${currentCardIndex === 0 ? 'disabled' : ''} class="px-3 py-1 bg-gray-200 dark:bg-gray-600 rounded disabled:opacity-50">Previous</button>
                            <button onclick="nextCard()" ${currentCardIndex === data.flashcards.length - 1 ? 'disabled' : ''} class="px-3 py-1 bg-gray-200 dark:bg-gray-600 rounded disabled:opacity-50">Next</button>
                        </div>
                    </div>
                </div>
            `;
        }

        function showAnswer() {
            const card = data.flashcards[currentCardIndex];
            document.getElementById('card-content').innerHTML = `
                <div class="text-lg font-medium mb-2 text-gray-600 dark:text-gray-400">Question:</div>
                <div class="mb-4">${card.front}</div>
                <div class="text-lg font-medium mb-2 text-green-600 dark:text-green-400">Answer:</div>
                <div class="mb-4 p-3 bg-green-50 dark:bg-green-900 rounded">${card.back}</div>
            `;
        }

        function previousCard() {
            if (currentCardIndex > 0) {
                currentCardIndex--;
                showStudyCard();
            }
        }

        function nextCard() {
            if (currentCardIndex < data.flashcards.length - 1) {
                currentCardIndex++;
                showStudyCard();
            }
        }

        function endSession() {
            studySessionActive = false;
            document.getElementById('study-session').innerHTML = `
                <p class="text-gray-500 dark:text-gray-400 mb-4">Study session completed!</p>
                <button onclick="startStudySession()" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-lg">
                    <i class="fas fa-play mr-2"></i>Start New Session
                </button>
            `;
        }

        // Form handlers
        document.getElementById('task-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const title = document.getElementById('task-title').value;
            const subject = document.getElementById('task-subject').value;
            const dueDate = document.getElementById('task-due-date').value;
            const priority = document.getElementById('task-priority').value;
            const description = document.getElementById('task-description').value;
            
            if (editingTask) {
                const task = data.tasks.find(t => t.id === editingTask);
                task.title = title;
                task.subject = subject;
                task.dueDate = dueDate;
                task.priority = priority;
                task.description = description;
                task.updatedAt = new Date();
            } else {
                const newTask = {
                    id: Date.now(),
                    title,
                    subject,
                    dueDate,
                    priority,
                    description,
                    completed: false,
                    createdAt: new Date()
                };
                data.tasks.push(newTask);
            }
            
            hideTaskForm();
            renderTasks();
            updateDashboard();
            renderCalendar();
        });

        document.getElementById('note-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const title = document.getElementById('note-title').value;
            const subject = document.getElementById('note-subject').value;
            const content = document.getElementById('note-content').value;
            const tags = document.getElementById('note-tags').value.split(',').map(t => t.trim()).filter(t => t);
            
            if (editingNote) {
                const note = data.notes.find(n => n.id === editingNote);
                note.title = title;
                note.subject = subject;
                note.content = content;
                note.tags = tags;
                note.updatedAt = new Date();
            } else {
                const newNote = {
                    id: Date.now(),
                    title,
                    subject,
                    content,
                    tags,
                    createdAt: new Date(),
                    updatedAt: new Date()
                };
                data.notes.push(newNote);
            }
            
            hideNoteForm();
            renderNotes();
            renderSubjectFilters();
            updateDashboard();
        });

        document.getElementById('flashcard-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const subject = document.getElementById('flashcard-subject').value;
            const front = document.getElementById('flashcard-front').value;
            const back = document.getElementById('flashcard-back').value;
            
            const newCard = {
                id: Date.now(),
                subject,
                front,
                back,
                createdAt: new Date()
            };
            
            data.flashcards.push(newCard);
            hideFlashcardForm();
            renderFlashcards();
            updateDashboard();
        });

        document.getElementById('note-search').addEventListener('input', renderNotes);

        // Utility functions
        function showConfirmDialog(message, onConfirm) {
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
            modal.innerHTML = `
                <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                    <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                    <div class="flex justify-end space-x-3">
                        <button class="px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded" onclick="this.closest('.fixed').remove()">Cancel</button>
                        <button class="px-4 py-2 bg-red-500 text-white hover:bg-red-600 rounded" onclick="this.closest('.fixed').remove(); (${onConfirm})()">Confirm</button>
                    </div>
                </div>
            `;
            document.body.appendChild(modal);
        }

        function showAlert(message) {
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
            modal.innerHTML = `
                <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                    <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                    <div class="flex justify-end">
                        <button class="px-4 py-2 bg-primary text-white hover:bg-primary-dark rounded" onclick="this.closest('.fixed').remove()">OK</button>
                    </div>
                </div>
            `;
            document.body.appendChild(modal);
        }

        function isToday(date) {
            const today = new Date();
            return date.toDateString() === today.toDateString();
        }

        function isThisWeek(date) {
            const today = new Date();
            const weekStart = new Date(today.setDate(today.getDate() - today.getDay()));
            const weekEnd = new Date(today.setDate(today.getDate() - today.getDay() + 6));
            return date >= weekStart && date <= weekEnd;
        }

        function formatDate(dateString) {
            const date = new Date(dateString);
            return date.toLocaleDateString();
        }

        function getPriorityColor(priority) {
            switch(priority) {
                case 'high': return 'border-red-500';
                case 'medium': return 'border-yellow-500';
                case 'low': return 'border-green-500';
                default: return 'border-gray-300';
            }
        }

        function getPriorityBadgeColor(priority) {
            switch(priority) {
                case 'high': return 'bg-red-100 text-red-800 dark:bg-red-900 dark:text-red-200';
                case 'medium': return 'bg-yellow-100 text-yellow-800 dark:bg-yellow-900 dark:text-yellow-200';
                case 'low': return 'bg-green-100 text-green-800 dark:bg-green-900 dark:text-green-200';
                default: return 'bg-gray-100 text-gray-800 dark:bg-gray-700 dark:text-gray-200';
            }
        }
    </script>
</body>
</html>
