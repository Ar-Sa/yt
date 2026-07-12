./components/admin/AdminConsole.tsx
Error: 
  x Unexpected token `div`. Expected jsx identifier
      ,-[/vercel/path0/components/admin/AdminConsole.tsx:1048:1]
 1048 |   // ── Render ───────────────────────────────────────────────────────────────────
 1049 | 
 1050 |   return (
 1051 |     <div className="min-h-screen bg-zinc-950 text-zinc-100 flex flex-col">
      :      ^^^
 1052 |       <ToastStack toasts={toasts} remove={removeToast} />
 1053 |       {showPwModal && <PasswordModal onClose={() => setShowPwModal(false)} onToast={addToast} />}
      `----
