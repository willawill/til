##ActiveRecord does migration in one transction. To break the transction:

- AR 4:

```
class Migration < ActiveRecord::Migration
  disable_ddl_transaction!

  def change
    add_index :asks, :active, algorithm: :concurrently
  end
end
```

- < AR 4

```
execute 'END'
execute 'CREATE INDEX CONCURRENTLY foo_bar_idx on bars'
execute 'BEGIN'
```
