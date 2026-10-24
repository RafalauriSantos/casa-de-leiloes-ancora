# casa-de-leiloes-ancora

Public, append-only record of bid-chain heads for the Casa de Leilões project.

Each line is one lot head: `lot_id, seq, head_hash, published_at`. Commits only add lines. The application publishes here; auditors compare the database history with these lines.

No personal data is stored here. Bidders appear only as hashes.
